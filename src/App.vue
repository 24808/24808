<template>
  <div id="app">
    <main-tab-bar></main-tab-bar>
    <!-- //路由 -->
    <keep-alive exclude="Detail">
      <router-view></router-view>
    </keep-alive>
  </div>
</template>

<script>
import MainTabBar from "./components/content/MainTabBar/MainTabBar";
export default {
  name: "App",
  components: { MainTabBar }
};
</script>

<style>
@import "assets/css/Base.css";
</style>
