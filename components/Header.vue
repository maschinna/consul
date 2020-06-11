<template>
  <div class="header">
      <div class="header__side">Particip8.io</div>
      <div class="header__center">
        <nuxt-link to="/">Overview</nuxt-link>
        <a href="mailto:parlameter@djnd.si">Contact</a>
        <nuxt-link to="/about">About the team</nuxt-link>
      </div>
      <div class="header__side">SL</div>
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

  .header {
      justify-content: center;
      display: flex;
      text-align: center;
      margin: 10px 0 10px 0;
      width: 100%;

      a {
        margin-left: 10px;
        margin-right: 10px;
      }

      &__side {
        width: 20%;
        margin: 0 10px 0 10px;
      }

      &__center {
        width: 60%;
        margin: 0 10px 0 10px;
        justify-content: space-between;
      }
    }
</style>