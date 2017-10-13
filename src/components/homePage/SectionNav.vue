<template>
  <div class="columns is-variable is-8">
    <div class="column">
      <p class="bd-notification is-info">教育资源<br/><i class="fa fa-book" aria-hidden="true"></i></p>
      
    </div>
    <div class="column">
      <p class="bd-notification is-success">幼儿活动<br/><i class="fa fa-bicycle" aria-hidden="true"></i></p>
      
    </div>
    <div class="column">
      <p class="bd-notification is-warning">师资力量<br/><i class="fa fa-id-badge" aria-hidden="true"></i></p>
    </div>
    <div class="column">
      <p class="bd-notification is-danger">照片墙<br/><i class="fa fa-picture-o" aria-hidden="true"></i></p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SectionNav'
  // data () {
  //   return {
  //     msg: 'Welcome to Your Vue.js App'
  //   }
  // }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
@import '../../assets/sass/SectionNavCss.scss'
</style>
