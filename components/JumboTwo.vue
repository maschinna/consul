<template>
  <div class="spacing__general">
    <h1 class="text--center color__title text--heading" style="margin: 70px 0 70px 0;">Z vami smo v vseh fazah procesa</h1>
    <div class="spacing__inner">
      <b-card-group deck>
        <b-card class="process-cards" img-src="~/assets/img/tile-image.png" img-alt="svetovanje" img-top>
          <div class="process-cards--content">
            <h2 class="text--uppercase text--italic">Svetovanje</h2>
            <div class="card-line"></div>
            <b-card-text>
              Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
            </b-card-text>
          </div>
        </b-card>

        <b-card class="process-cards" img-src="~/assets/img/tile-image.png" img-alt="razvoj" img-top>
          <div class="process-cards--content">
            <h2 class="text--uppercase text--italic">Razvoj</h2>
            <div class="card-line"></div>
            <b-card-text>
              Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
            </b-card-text>
          </div>
        </b-card>

        <b-card class="process-cards" img-src="~/assets/img/tile-image.png" img-alt="podpora" img-top>
          <div class="process-cards--content">
            <h2 class="text--uppercase text--italic">Podpora</h2>
            <div class="card-line"></div>
            <b-card-text>
              Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
            </b-card-text>
          </div>
        </b-card>
      </b-card-group>
    </div>
  </div>
</template>

<script>
    export default {
        name: "JumboTwo"
    }
</script>

<style scoped lang="scss">
@import './assets/style/common.scss';

  .card-line {
    width: 122px;
    height: 5px;
    margin-bottom: 10px;
    background-image: linear-gradient(to right, #f0b9ad 0%, #d9dbf1 100%);
  }

  .process-cards{
    border: none;

    img {
      width: 60%;
      margin-bottom: -20px;
      margin-left: 20%;
    }

    &--content{
      box-shadow: 0 0 37px rgba(26, 29, 64, 0.2);
      background-color: #ffffff;
      padding: 20px 20px 20px 20px;
    }
  }
</style>