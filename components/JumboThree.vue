<template>
  <div class="flex blue-banner color__blue">
    <div class="blue-banner--elements flex flex--column flex-justify--space-between">
      <div class="flex-grid">
        <div class="flex-grid__col-30">
          <h1 class="text--heading text--italic color__title text--left">Organizacije, ki nam že zaupajo</h1>
        </div>
        <div class="flex-grid__col-30" style="border: 4px solid #32366a;">
          <img src="~/assets/img/mo-koper.png" />
          <b-button href="/references/koper" class="blue-banner--button" pill>Študija primera</b-button>
        </div>
        <div class="flex-grid__col-30" style="border: 4px solid #32366a;">
          <img src="~/assets/img/ob-hrpelje-kozina.png" />
          <b-button href="/references/kozina" class="blue-banner--button" pill>Študija primera</b-button>
        </div>
      </div>
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

  .flex-grid {
    display: flex;
    justify-content: space-evenly;

    h1{
      align-items: center;
    }

    &__col-30 {
      width: 30%;
    }
  }

  @media (max-width: 900px) {
    .flex-grid {
      display: block;

      &__col-30 {
        width: 100%;
        margin-bottom: 40px;
      }
    }
  }

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