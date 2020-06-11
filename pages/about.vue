<template>
  <div>
    <Header />

    <BannerAbout />

    <div class="flex spacing__general spacing__inner first-section">
      <b-col cols="6">
        <b-row>
          <p>Our network of members and volunteers includes a diverse variety of background experiences, ranging from leading Slovenian
            tech companies (Outfit 7, Celtra, Nexto, Reciprocity, Proxima), marketing agencies (Renderspace, Luna, Futura), universities
            (University of Ljubljana, Cornell University, University of London), research institutions (World Debate Institute, Institute
            Jožef Stefan), art collectives (ZEK Crew) and NGOs (CNVOS, Greenpeace, Pro et contra - Institute for the culture of dialogue,
            different labour unions).</p>
        </b-row>
      </b-col>
      <b-col cols="6">
        <b-row>
          <img src="~/assets/img/tile-image.png" />
        </b-row>
      </b-col>
    </div>

    <div class="flex spacing__general spacing__inner first-section">
      <b-col cols="6">
        <b-row>
          <img src="~/assets/img/tile-image.png" />
        </b-row>
      </b-col>
      <b-col cols="6">
        <b-row>
          <p>Our projects have received funding by Google DNI (applied to 4 rounds, received 3), NED and American Embassy in Slovenia,
            and have been awarded within the designer/developer community (Brumen award, several Diggit awards ...). Our projects and
            accomplishments are regularly featured in mainstream and indie media and we are often invited to speak at important public
            events at home and abroad.</p>
        </b-row>
      </b-col>
    </div>

    <JumboFour />
    <Footer />

  </div>
</template>

<script>
import BannerAbout from "../components/BannerAbout";
import Footer from "../components/Footer";
import JumboFour from "../components/JumboFour";
import Header from "../components/Header";

export default {
  components: {
      Header,
      BannerAbout,
      Footer,
      JumboFour
  }
}
</script>

<style scoped lang="scss">
    @import './assets/style/common.scss';

    .first-section {
      flex-wrap: wrap;
      display: flex;
      flex-direction: row;
      align-items: center;
      margin-left: 20%;
      margin-right: 20%;


      img {
        width: 200px;
        margin-left: 10%;
      }
    }
</style>
