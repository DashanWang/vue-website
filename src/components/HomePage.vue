<template>
  <div>
    <HomeSlider></HomeSlider>
    <SectionNav></SectionNav>
  </div>
</template>

<script>
import HomeSlider from './homePage/HomeSlider.vue'
import SectionNav from './homePage/SectionNav.vue'

export default {
  name: 'homePage',
  // data () {
  //   return {
  //     msg: 'Welcome to Your Vue.js App'
  //   }
  // },
  components: {
    'HomeSlider': HomeSlider,
    'SectionNav': SectionNav
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>

</style>
