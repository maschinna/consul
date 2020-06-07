<template>
     <b-jumbotron class="spacing__general color__base">
        <b-row>
          <b-col class="banner__home">
            <h1 class="text--heading color__title">Demokracija je temelj zaupanja</h1>
            <p class="text--banner-subtitle color__title">Celovita rešitev za vodenje participativnega odločanja s pomočjo digitalnih orodij.</p>
          </b-col>
          <b-col>
              <img style="width: 50%;" src="~/assets/img/banner-home.png" />
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
    .banner {
      &__home {
        margin-left: 20%;

        p {
          margin-right: 20%;
        }
      }
    }
</style>