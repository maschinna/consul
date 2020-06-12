<template>
  <div class="footer flex spacing__general text-center">
      <div class="flex-grid">
          <div class="flex-grid__col-30">
            <p class="text--banner-subtitle color__title">Developed by</p>
            <a href="https://danesjenovdan.si/" target="_blank">
              <img src="~/assets/img/djnd-logo.png" style="width: 100px;"/>
            </a>
          </div>
          <div class="flex-grid__col-30">
            <img src="~/assets/svg/heart.svg" style="width: 20px;"/>
            <p class="text--banner-subtitle color__title">Consul is an open-source solution.</p>
            <a href="https://github.com/danesjenovdan" target="_blank">
              <img src="~/assets/img/github-button.png" style="width: 80px;"/>
            </a>
          </div>
          <div class="flex-grid__col-30">
            <p class="text--banner-subtitle color__title">We are part of</p>
            <div class="flex-grid">
              <div class="flex-grid__col-50">
                <img src="~/assets/img/consul-logo.png" style="width: 80px;"/>
              </div>
              <div class="flex-grid__col-50">
                <p style="color: black; text-align: left;" class="text-weight--600">CONSUL<br>
                DEMOCRACY<br>
                  foundation</p>
              </div>
            </div>
          </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Footer"
    }
</script>

<style scoped lang="scss">
  @import './assets/style/common.scss';

  .flex-grid {
    display: flex;

    &__col-30 {
      width: 30%;
      margin: 0 30px 0 30px;
    }

    &__col-50 {
      width: 50%;
    }
  }

  @media (max-width: 900px) {
    .flex-grid {
      display: block;

      &__col-30 {
        width: 100%;
        margin-bottom: 40px;
      }

      &__col-50 {
        width: 100%;

        p {
          text-align: center !important;
          margin-top: 20px;
        }
      }
    }
  }

  .footer {
      flex-wrap: wrap;
      flex-direction: row;
      justify-content: center;
      margin-top: 50px !important;
      margin-bottom: 20px !important;
    }
</style>