<template>
     <b-jumbotron class="spacing__general color__base">
        <b-row class="banner-home">
          <b-col cols="3" class="banner-home--title">
            <h1 class="text--heading color__title">Demokracija je temelj zaupanja</h1>
            <p class="text--banner-subtitle color__title">Celovita rešitev za vodenje participativnega odločanja s pomočjo digitalnih orodij.</p>
          </b-col>
          <b-col cols="4" class="banner-home--picture">
              <img src="~/assets/img/banner-home.png" />
          </b-col>
        </b-row>
      </b-jumbotron>
</template>

<script>
    export default {
        name: "BannerHome"
    }
</script>

<style scoped lang="scss">
  @import './assets/style/common.scss';
    .banner-home {
      display: flex;
      flex-wrap: wrap;

      &--title {
        margin-left: 20%;

        p {
          margin-right: 20%;
        }
      }

      &--picture {

        img{
          max-width: 100%;
          max-height: 100%;
        }
      }
    }
</style>