<template>
  <div id="app">
    <div class="banner_shop">
      <div class="container">
        <div>
          <img src="../assets/img/buy-comics-digital-comics.png" alt="digital comics">
          <h4>digital comics</h4>
        </div>
        <div>
          <img src="../assets/img/buy-comics-merchandise.png" alt="merchandise">
          <h4>DC merchandise</h4>
        </div>
        <div>
          <img src="../assets/img/buy-comics-subscriptions.png" alt="subscriptions">
          <h4>subscription</h4>
        </div>
        <div>
          <img src="../assets/img/buy-comics-shop-locator.png" alt="shop locator">
          <h4>shop locator</h4>
        </div>
        <div>
          <img src="../assets/img/buy-dc-power-visa.svg" alt="power visa">
          <h4>dc power visa</h4>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'BannerShop',
}
</script>

<style lang="scss" scoped>
    .banner_shop {
      height: 150px;
      width: 100%;
      position: relative;
      z-index: 2;
      background-color: #0282f9;
      div {
        display: flex;
        align-items: center;
      }

      img {
        height: 60px;
      }

      h4 {
        margin: 10px;
        text-transform: uppercase;
        color: white;
      }
    }

    .container {
      width: 70%;
      height: 100%;
      margin: auto;
      display: flex;
      justify-content: space-evenly;
      align-items: center;
    }

</style>