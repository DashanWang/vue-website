<template>
  <div class="columns bg">
    <div class="section1">
      <h2>辅仁实验幼儿园</h2>
      <small></small>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeSlider',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
.bg {
  height: 35em;
  background: url("../../../static/img/19-copy1.png") no-repeat fixed;
  background-size: contain;
  .section1 {
    // border: 2px solid;
    border-radius: 30px;
    align-self: center;
    position: relative;
    top: 10%;
    left: 10%;
    background-color: #ffa100;
    height: 15em;
    width: 40%;
    padding:1em 1em 1em 1em;
    h2{
      font-size:3em;
      font-weight: bold;
      color:white;
    }
  }
}
</style>
