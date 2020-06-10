<template>
  <div class="flex blue-banner color__blue">
    <div class="blue-banner--elements flex flex--column flex-justify--space-between">
      <b-row style="justify-content: space-evenly;">
        <b-col cols="3">
          <h1 class="text--heading text--italic color__title text--left">Organizacije, ki nam že zaupajo</h1>
        </b-col>
        <b-col cols="3" style="border: 4px solid #32366a;">
          <img src="~/assets/img/mo-koper.png" />
          <b-button href="#" class="blue-banner--button" pill>Študija primera</b-button>
        </b-col>
        <b-col cols="3" style="border: 4px solid #32366a;">
          <img src="~/assets/img/mo-koper.png" />
          <b-button href="#" class="blue-banner--button" pill>Študija primera</b-button>
        </b-col>
      </b-row>
    </div>
  </div>
</template>

<script>
    export default {
        name: "JumboThree"
    }
</script>

<style scoped lang="scss">
  @import './assets/style/common.scss';

  .blue-banner {
    text-align: center;
    display: flex;
    margin-bottom: 70px;

    &--elements{
      margin: 40px 10% 40px 10%;
    }

    &--button{
      background-color: #7c7fae;
      width: 70%;
      margin-left: 20%;
      margin-bottom: -20px;
    }

    img {
      padding: 20% 20%;
      max-width: 100%;
      max-height: 100%;
    }
  }

</style>