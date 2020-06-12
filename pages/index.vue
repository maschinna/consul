<template>
  <div>
    <Header />

    <BannerHome />

    <div class="first-section spacing__resp">
      <p class="text--above-heading">Participativno odločanje za vašo</p>
      <h2 class="text--heading color__title">organizacijo.</h2>
    </div>

    <JumboOne />
    <JumboTwo />
    <JumboThree />
    <JumboFour />

    <Footer />

  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import BannerHome from "../components/BannerHome";
import JumboOne from "../components/JumboOne";
import JumboTwo from "../components/JumboTwo";
import JumboThree from "../components/JumboThree";
import JumboFour from "../components/JumboFour";
import Footer from "../components/Footer";
import Header from "../components/Header";

export default {
  components: {
      Header,
      Footer,
      JumboFour,
      JumboThree,
      JumboTwo,
      JumboOne,
      BannerHome,
    Logo
  }
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

      &__col-50 {
        width: 50%;
      }
    }

    @media (max-width: 900px) {
      .flex-grid {
        display: block;

        &__col-50 {
          width: 100%;
          margin-bottom: 40px;
        }
      }
    }

    .first-section {
      text-align: center;
      margin: 40px 0 40px 0;
    }
</style>
