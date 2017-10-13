<template>
  <div id="app">
    <TopNav />
    <router-view></router-view>
  </div>
</template>

<script>
import TopNav from './components/navs/TopNav.vue'
export default {
  name: 'app',
  components: {
    'TopNav': TopNav
  }
}
</script>

<style lang="scss">
#app {
    /* font-family: 'Avenir', Helvetica, Arial, sans-serif;  */
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height:100%;
}
</style>
