<template>
  <b-jumbotron class="spacing__general color__base">
        <div class="banner-koper">
          <h2 class="text--heading color__title">Študija primera</h2>
          <p class="text--banner-subtitle color__title">Mestna občina Koper</strong></p>
        </div>
  </b-jumbotron>
</template>

<script>
    export default {
        name: "BannerKoper"
    }
</script>

<style scoped lang="scss">
  @import './assets/style/common.scss';

  .banner-koper {
    display: flex;
    flex-flow: column;
    justify-content: center;
    text-align: center;
    /*background-image: url("~/assets/img/djnd-team.png");*/
  }

</style>