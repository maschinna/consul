<template>
     <b-jumbotron class="spacing__general color__base jumbo-image">
        <div class="banner-about">
          <h2 class="text--heading color__title">Kdo smo</h2>
          <p class="text--banner-subtitle color__title">S Consulom upravlja <strong>Danes je nov dan, Inštitut za druga vprašanja</strong></p>
        </div>
      </b-jumbotron>
</template>

<script>
    export default {
        name: "BannerAbout"
    }
</script>

<style scoped lang="scss">
  @import './assets/style/common.scss';

  .banner-about {
    display: flex;
    flex-flow: column;
    justify-content: center;
    text-align: center;
    background-image: url("/assets/img/djnd-team.png");
  }

</style>