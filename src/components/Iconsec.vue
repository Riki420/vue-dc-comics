<template>
  <section class="icon-section">
      <div class="container">
          <div class="row">
              <div class="col-icon">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="" class="w-25">
                    <span class="txt-big">Digital Comics</span>
              </div>
              <div class="col-icon">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="" class="w-25">
                    <span class="txt-big">Merchandise</span>
              </div>
              <div class="col-icon">
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="" class="w-25">
                    <span class="txt-big">Shop Locator</span>
              </div>
              <div class="col-icon">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="" class="w-25">
                    <span class="txt-big">Subscriptions</span>
              </div>
              <div class="col-icon">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="" class="w-25">
                    <span class="txt-big">Power Visa</span>
              </div>
          </div>
      </div>
  </section>
</template>

<script>
export default {
    name: "Iconsec"
}
</script>

<style lang="scss" scoped>

@import "../assets/scss/vars.scss";

    .icon-section{
        height: 200px;
        background-color: $dc-color;
    }

    .col-icon{
        display: flex;
        align-content: center;
        align-items: center;
        justify-content: center;
        font-size: 1.4em;
        color: #fff;
        height: 200px;
        width: 20%;
        img{
            margin-right: 10px;
        }
        &:hover{
            opacity: 0.5;
            cursor: pointer;
        }
    }

</style>