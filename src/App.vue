<template>
  <div id="app">
    <Header />
    <Main />
    <Iconsec />
    <Footer />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Main from "@/components/Main.vue";
import Iconsec from "@/components/Iconsec.vue"
import Footer from "@/components/Footer.vue";
export default {
  name: 'App',
  components: {
    Header,
    Main,
    Iconsec,
    Footer
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Saira+Extra+Condensed&display=swap');
@import "./assets/scss/style.scss";
 
  
  .row{
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: start;
  }
  
</style>
