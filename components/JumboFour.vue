<template>
  <b-jumbotron class="spacing__general color__base">
    <div class="flex flex-wrap contact">
      <b-row class="spacing__inner-banner">
        <b-col cols="6">
          <b-media left-align vertical-align="center">
            <template v-slot:aside>
              <b-img src="~/assets/img/kontaktiraj-nas.png" width="60" alt="kontaktirajte-nas"></b-img>
            </template>
            <h2 class="color__title text-weight--700" style="margin-top: 50px;">Kontaktiraj nas.</h2>
            <p>
              Make sure today that you comply with the standards of tomorrow.
            </p>
            <p>
              Contact us on <a href="mailto:parlameter@djnd.si">parlameter(at)djnd.si</a>.
            </p>
          </b-media>
        </b-col>
        <b-col cols="6">
          <b-media left-align vertical-align="center">
            <template v-slot:aside>
              <b-img src="~/assets/img/o-ekipi.png" width="60" alt="o-ekipi"></b-img>
            </template>
            <h2 class="color__title text-weight--700" style="margin-top: 50px;">O ekipi.</h2>
            <p>
              Preverite, kako smo fajn in zaupanja vredni.
            </p>
            <p>
              <a href="mailto:parlameter@djnd.si">DJND ekipa</a>.
            </p>
          </b-media>
        </b-col>
      </b-row>
    </div>
  </b-jumbotron>
</template>

<script>
    export default {
        name: "JumboFour"
    }
</script>

<style scoped lang="scss">
  @import './assets/style/common.scss';

  a {
    color: #32366a;
    font-weight: 600;
  }
  .contact{
    img {
      width: 252px;
    }
  }
</style>