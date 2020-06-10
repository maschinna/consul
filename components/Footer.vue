<template>
  <div class="footer flex spacing__general text-center">
      <b-row>
          <b-col cols="3">
            <p class="text--banner-subtitle color__title">Developed by</p>
            <a href="https://danesjenovdan.si/" target="_blank">
              <img src="~/assets/img/djnd-logo.png" style="width: 100px;"/>
            </a>
          </b-col>
          <b-col cols="6">
            <img src="~/assets/svg/heart.svg" style="width: 20px;"/>
            <p class="text--banner-subtitle color__title">Consul is an open-source solution.</p>
            <a href="https://github.com/danesjenovdan" target="_blank">
              <img src="~/assets/img/github-button.png" style="width: 80px;"/>
            </a>
          </b-col>
          <b-col cols="3">
            <p class="text--banner-subtitle color__title">We are part of</p>
            <b-row>
              <b-col cols="6">
                <img src="~/assets/img/consul-logo.png" style="width: 80px;"/>
              </b-col>
              <b-col cols="6">
                <p style="color: black; text-align: left;" class="text-weight--600">CONSUL<br>
                DEMOCRACY<br>
                  foundation</p>
              </b-col>
              <b-col
            </b-row>
          </b-col>
        </b-row>
    </div>
</template>

<script>
    export default {
        name: "Footer"
    }
</script>

<style scoped lang="scss">
  @import './assets/style/common.scss';

  .footer {
      flex-wrap: wrap;
      flex-direction: row;
      justify-content: center;
      margin: 40px 0 10px 0;
    }
</style>