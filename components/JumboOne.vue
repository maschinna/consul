<template>
  <div class="color__pale spacing__general">
    <div class="flex flex--column">
      <h1 style="padding: 50px 20% 20px 20%;" class="text--center color__title text--heading">Consul je celovita rešitev za vodenje participativnega odločanja</h1>
      <b-row class="spacing__inner">
        <b-col cols="8">
          <div class="webscreen">
            <div class="text--center color__base" style="padding: 10px 0 10px 0;">
              <strong>Predlagam-odločam</strong> / Mestna občina Koper
            </div>
            <div class="webscreen--article" style="margin: 20px 20px 20px 20px;">
              <h2 class="text-weight--700" style="margin-top: 20px;">Ureditev pločnika do Vrtca Škofije</h2>
              <p>Edi Mavsar - 29. 09. 2019 - Območje 3</p>
              <img src="https://www.toronto.ca/wp-content/uploads/2017/11/997d-Parking-Residential-On-street.jpg" />
            </div>
            <div class="webscreen--article-content color__base-light">
              <p>Zakaj ta predlog?</p>
              <p>{{ accordionItem }}</p>
            </div>
          </div>
        </b-col>
        <b-col cols="4">
          <div class="sidebar flex flex--column">
            <div class="card--left-border">
              <h2 v-b-toggle.accordion-1 class="m-1 color__title text-weight--700">Uporabniku prijazno zbiranje predlogov</h2>
              <b-collapse visible id="accordion-1" accordion="my-accordion">
                <b-card class="card--style">{{ accordionItem }}</b-card>
              </b-collapse>
            </div>
            <div class="card--left-border">
              <h2 v-b-toggle.accordion-2 class="m-1 color__title text-weight--700">Varen sistem glasovanja</h2>
              <b-collapse id="accordion-2" accordion="my-accordion">
                <b-card class="card--style">{{ accordionItem }}</b-card>
              </b-collapse>
            </div>
            <div class="card--left-border">
              <h2 v-b-toggle.accordion-3 class="m-1 color__title text-weight--700">Mobilnim napravam prijazno</h2>
              <b-collapse id="accordion-3" accordion="my-accordion">
                <b-card class="card--style">{{ accordionItem }}</b-card>
              </b-collapse>
            </div>
            <div class="card--left-border">
              <h2 v-b-toggle.accordion-4 class="m-1 color__title text-weight--700">Enostavno urednikovanje</h2>
              <b-collapse id="accordion-4" accordion="my-accordion">
                <b-card class="card--style">{{ accordionItem }}</b-card>
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
    background-color: white;

    &--article img{
      width: 100%;
    }

    &--article-content{
      margin: 40px 10% 0 10%;
      padding: 20px 20px 20px 20px;
    }

    .sidebar {
      border-left: 8px solid black;
      height: 100%;
    }
  }

  .card {
    &--style{
      background-color: transparent;
      border: none;
    }

    &--left-border{
      border-left: solid 3px #f0b9ad;
      margin-bottom: 40px;
      padding-left: 10px;
    }
  }
</style>