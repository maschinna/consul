<template>
  <div class="spacing__general">
    <h1 class="text--center">Z vami smo v vseh fazah procesa</h1>
    <div class="spacing__inner">
      <b-card-group deck>
        <b-card img-src="~/assets/img/tile-image.png" img-alt="svetovanje" img-top>
          <h2 class="text--uppercase text--italic">Svetovanje</h2>
          <div class="card-line"></div>
          <b-card-text>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </b-card-text>
        </b-card>

        <b-card img-src="~/assets/img/tile-image.png" img-alt="razvoj" img-top>
          <h2 class="text--uppercase text--italic">Razvoj</h2>
          <div class="card-line"></div>
          <b-card-text>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </b-card-text>
        </b-card>

        <b-card img-src="~/assets/img/tile-image.png" img-alt="podpora" img-top>
          <h2 class="text--uppercase text--italic">Podpora</h2>
          <div class="card-line"></div>
          <b-card-text>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </b-card-text>
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
    height: 7px;
    margin-bottom: 10px;
    background-image: linear-gradient(to right, #f0b9ad 0%, #d9dbf1 100%);
  }
</style>