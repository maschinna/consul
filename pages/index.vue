<template>
  <div>
    <div class="header">
      <div class="header__side">Particip8.io</div>
      <div class="header__center">
        <a href="#">Overview</a>
        <a href="#">Contact</a>
        <a href="#">About the team</a>
      </div>
      <div class="header__side">SL</div>
    </div>

    <BannerHome />

    <div class="first-section">
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

export default {
  components: {
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

    a {
      color: black;
    }

    .first-section {
      justify-content: center;
      text-align: center;
      margin: 40px 0 40px 0;
    }

    .header {
      justify-content: center;
      display: flex;
      text-align: center;
      margin: 10px 0 10px 0;
      width: 100%;

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
