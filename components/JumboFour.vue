<template>
  <b-jumbotron class="spacing__general color__base">
    <div class="flex flex-wrap contact">
      <div class="flex-grid spacing__inner-banner">
        <div class="flex-grid__col-60 spacing__resp">
          <b-media left-align vertical-align="center" class="flex" style="align-items: center;">
            <template v-slot:aside>
              <b-img src="~/assets/img/kontaktiraj-nas.png" alt="kontaktirajte-nas"></b-img>
            </template>
            <h2 class="color__title text-weight--700">Kontaktiraj nas.</h2>
            <p>
              Make sure today that you comply with the standards of tomorrow.
            </p>
            <p>
              Contact us on <a href="mailto:parlameter@djnd.si">parlameter(at)djnd.si</a>.
            </p>
          </b-media>
        </div>
        <div class="flex-grid__col-60 spacing__resp">
          <b-media left-align vertical-align="center" class="flex" style="align-items: center;">
            <template v-slot:aside>
              <b-img src="~/assets/img/o-ekipi.png" alt="o-ekipi"></b-img>
            </template>
            <h2 class="color__title text-weight--700">O ekipi.</h2>
            <p>
              Preverite, kako smo fajn in zaupanja vredni.
            </p>
            <p>
              <nuxt-link to="/about">DJND ekipa</nuxt-link>.
            </p>
          </b-media>
        </div>
      </div>
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

  .flex-grid{
    display: flex;

    &__col-60{
      width: 50%;
    }
  }

  @media (max-width: 900px) {
    .flex-grid {
      display: block;

      &__col-60 {
        width: 100%;
        margin-bottom: 40px;
      }
    }
  }

  a {
    color: #32366a;
    font-weight: 600;
  }
  .contact{
    img {
      width: 170px;
    }
  }
</style>