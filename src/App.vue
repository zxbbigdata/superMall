<template>
  <div id="app">
    <routerView></routerView>
    <main-tab-bar/>
  </div>
</template>
<script>
import MainTabBar from 'components/content/mainTabbar/MainTabBar'
export default {
  name: 'app',
  components: {MainTabBar}
}
</script>
<style>
  @import "assets/css/base.css";
</style>
