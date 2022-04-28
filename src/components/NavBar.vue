<template>
  <div>
    <a href="#">{{ name }}</a>
  </div>
</template>

<script>
export default {
  name: "NavBar",
  props: {
    name: String,
  },
};
</script>

<style lang="scss" scoped>
@import "../style/general.scss";

a {
  text-decoration: none;
  color: $nav-grey;
  font-size: 14px;
  font-weight: bold;
  &:hover {
    color: $bg-blue;
    transition: 200ms;
  }
}
</style>