<template>
  <header>
    <div id="upper">
      <div class="d-flex container">
        <p>Everything about Lifestyle, Travel and Gadgets!</p>
        <ul class="d-flex">
          <li><a href="#">SIGN IN</a></li>
          <li><a href="#">ABOUT US</a></li>
          <li><a href="#">CONTACT US</a></li>
          <li><a href="#">BUY NOW</a></li>
        </ul>
      </div>
    </div>
    <div id="logo">
      <div class="container">
        <img src="../assets/img/logo-default-slim.png" alt="logo" />
      </div>
    </div>
    <div id="navbar">
      <div class="container d-flex">
        <NavBar v-for="item in navlist" :name="item.name" :key="item.id" />
      </div>
    </div>
  </header>
</template>

<script>
import NavBar from "./NavBar.vue";

export default {
  name: "HeaderComp",
  components: {
    NavBar,
  },
  props: {
    navlist: Array,
  },
};
</script>

<style lang="scss" scoped>
@import "../style/general.scss";
#upper {
  background-color: $bg-blue;
  font-size: 11px;
  padding: 20px 0;
  p {
    color: $white-grey;
    margin-right: 20px;
    font-weight: bold;
  }
  ul {
    column-gap: 20px;
    li {
      list-style: none;
      a {
        color: $white;
        text-decoration: none;
      }
    }
  }
}

#logo {
  background-color: $white;
  padding: 40px 0;
  img {
    width: 8%;
  }
  margin-bottom: 2px;
}

#navbar {
  background-color: $white;
  padding: 20px 0;
  div {
    &:first-child {
      column-gap: 50px;
    }
  }
}
</style>