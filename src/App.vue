<template>
  <div id="app">
    <Header :navlist="navlist" />
    <Main />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/HeaderComp.vue";
import Main from "./components/MainComp.vue";
import Footer from "./components/FooterComp.vue";

import navlist from "./assets/data/navbar.json";

export default {
  name: "App",
  components: {
    Header,
    Main,
    Footer,
  },
  data() {
    return {
      navlist,
    };
  },
};
</script>

<style lang="scss">
@import "./style/general.scss";
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: sans-serif;
  #app {
    background-color: $white-grey;
  }
}
</style>
