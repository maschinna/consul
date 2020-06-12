<template>
  <div class="header">
      <div class="header__side-left">Particip8.io</div>
      <div class="header__center spacing__resp">
        <nuxt-link to="/">Overview</nuxt-link>
        <a href="mailto:parlameter@djnd.si">Contact</a>
        <nuxt-link to="/about">About the team</nuxt-link>
      </div>

      <div class="dropdown header__side-right">
        <button class="dropbtn">SL</button>
        <div class="dropdown-content">
        <a href="#">EN</a>
        </div>
      </div>
    </div>
</template>

<script>
    export default {
        name: "Header"
    }
</script>

<style scoped lang="scss">
  @import './assets/style/common.scss';

  a {
      color: black;
  }

  .dropbtn {
    background-color: white;
    border: solid black 1px;
    padding: 0 15px 0 15px;
    font-size: 16px;
    cursor: pointer;
  }

  .dropdown {
    position: relative;
    display: inline-block;
  }

  .dropdown-content {
    display: none;
    position: absolute;
    right: 0;
    background-color: #f9f9f9;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
  }

  .dropdown-content a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
  }

  .dropdown-content a:hover {background-color: #f1f1f1;}

  .dropdown:hover .dropdown-content {
    display: block;
  }

  .dropdown:hover .dropbtn {
    background-color: #f2d0c9;
  }

  .header {
    align-items: center;
    display: flex;
    flex-flow: row wrap;
    margin: 10px 0 10px 0;
    width: 100%;

    a {
      margin-left: 10px;
      margin-right: 10px;
    }

    &__side-left {
      margin-left: 3%;
      margin-right: -2%;
      float: left;
      font-size: 20px;
      order: 1;
    }

    &__side-right {
      margin-right: 3%;
      float: right;
      order: 3;
    }

    &__center {
      justify-content: center;
      margin: auto;
      order: 2;
    }
  }
</style>