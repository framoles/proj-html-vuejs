<template>
  <div>
    <JumboTron />
    <PostList />
    <CategoryNav />
    <PostView />
  </div>
</template>

<script>
import JumboTron from "./JumboTron.vue";
import PostList from "./PostList.vue";
import CategoryNav from "./CategoryNav.vue";
import PostView from "./PostView.vue";

export default {
  name: "MainComp",
  components: {
    JumboTron,
    PostList,
    CategoryNav,
    PostView,
  },
};
</script>

<style>
</style>