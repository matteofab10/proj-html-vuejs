<template>
  <div>
    <Header />
    <Main />
    <Footer :creditsLinks="footerCreditsLinks"/>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";

export default {
  name: 'App',
  data() {
    return {
      footerCreditsLinks: [
        {
          title: 'Copyright 2002 - 20019 Avada',
          link: '#'
        },
        {
          title: 'All Rights Reserver',
          link: '#'
        },
        {
          title: 'Powered by WordPress',
          link: '#'
        },
        {
          title: 'ThemeFusion',
          link: '#'
        },
      ]
    }
  },
  components: {
    Header,
    Main,
    Footer
  }
}

</script>

<style lang="scss">
@import "./assets/style/generals.scss";
@import url('https://fonts.googleapis.com/css2?family=Spectral:ital,wght@0,400;0,700;1,400&display=swap');

</style>
