<template>
  <div class="container">
    <div id="nav" class="d-flex">
      <span>&#60;</span>
      <ul class="d-flex">
        <li>GADGETS</li>
        <li>PHOTOGRAPHY</li>
        <li>LIFESTYLE</li>
        <li>FASHION</li>
        <li>RECIPES</li>
        <li>TRAVEL</li>
      </ul>
      <span>&#62;</span>
    </div>
  </div>
</template>

<script>
export default {
  name: "CategoryNav",
};
</script>

<style lang="scss" scoped>
@import "../style/general.scss";
div {
  background-color: $bg-blue;
  #nav {
    padding: 30px 0;
    justify-content: center;
    align-items: center;
    span {
      padding: 20px;
    }
    ul {
      column-gap: 40px;
      li {
        cursor: pointer;
        list-style: none;
        padding: 15px 55px;
        background-color: #212529;
        color: $white;
        font-size: 13px;
        font-weight: 800;
        &:hover {
          background-color: #404040;
          transition: 200ms;
        }
      }
    }
  }
}
</style>