<template>
  <div id="app">
    <Header />

    <main>
      <Main />
      <BannerShop />
    </main>

    <Footer />
 
  </div>
</template>

<script>
import Header from './components/Header.vue'; 
import Main from './components/Main.vue';  
import Footer from './components/Footer.vue'
import BannerShop from './components/BannerShop.vue'

export default {
  name: 'App',
  components: {
    Header, 
    Main,
    BannerShop,
    Footer
  }
}
</script>

<style lang="scss">
  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-family: 'Oswald', sans-serif;
  }
</style>
