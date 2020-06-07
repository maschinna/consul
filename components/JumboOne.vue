<template>
  <div class="color__pale spacing__general">
    <div>
      <h1 class="text--center color__title text--heading spacing__general">Consul je celovita rešitev za vodenje participativnega odločanja</h1>
      <b-row class="spacing__inner">
        <b-col cols="8">
          <div class="webscreen">
            <div class="text--center color__base">
              <strong>Predlagam-odločam</strong> / Mestna občina Koper
            </div>
            <div class="webscreen--article">
              <h2>Ureditev pločnika do Vrtca Škofije</h2>
              <p>Edi Mavsar - 29. 09. 2019 - Območje 3</p>
              <img src="https://www.toronto.ca/wp-content/uploads/2017/11/997d-Parking-Residential-On-street.jpg" />
            </div>
            <div class="webscreen--article-content color__base">
              <p>Zakaj ta predlog?</p>
              <p>{{ accordionItem }}</p>
            </div>
          </div>
        </b-col>
        <b-col cols="4">
          <div class="sidebar">
            <div clas="sidebar--card">
              <h2 v-b-toggle.collapse-1 class="m-1">Uporabniku prijazno zbiranje predlogov</h2>
              <b-collapse visible id="collapse-1">
                <b-card>{{ accordionItem }}</b-card>
              </b-collapse>
            </div>
            <div clas="sidebar--card">
              <h2 v-b-toggle.collapse-2 class="m-1">Varen sistem glasovanja</h2>
              <b-collapse id="collapse-2">
                <b-card>{{ accordionItem }}</b-card>
              </b-collapse>
            </div>
            <div clas="sidebar--card">
              <h2 v-b-toggle.collapse-3 class="m-1">Mobilnim napravam prijazno</h2>
              <b-collapse id="collapse-3">
                <b-card>{{ accordionItem }}</b-card>
              </b-collapse>
            </div>
            <div clas="sidebar--card">
              <h2 v-b-toggle.collapse-4 class="m-1">Enostavno urednikovanje</h2>
              <b-collapse id="collapse-4">
                <b-card>{{ accordionItem }}</b-card>
              </b-collapse>
            </div>
          </div>
        </b-col>
      </b-row>
    </div>
  </div>

</template>

<script>
    export default {
        name: "JumboOne",
        data() {
            return {
                accordionItem: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat'
            }
        }
    }
</script>

<style scoped lang="scss">
  @import './assets/style/common.scss';

  .webscreen {
    border: solid #f0b9ad;
    background-color: white;

    &--article img{
      width: 100%;
    }

    &--article-content{
      margin: 40px 10% 0 10%;
    }

    .sidebar {
      border-left: 8px solid black;
      height: 100%;
    }
  }
</style>