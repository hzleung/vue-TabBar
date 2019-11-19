<template>
  <div id="app">
    <router-view></router-view>
    <main-tab-bar/>
  </div>
</template>

<script>
import MainTabBar from './components/MainTabBar'
export default {
  name: "App",
  components: {
    // TabBar会被自动解析为驼峰语法：tab-bar
    MainTabBar
  }
};
</script>

<style>
@import url("./assets/css/base.css");
</style>
