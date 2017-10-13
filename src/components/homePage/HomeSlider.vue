<template>
  <div class="columns bg">
    <div class="section1">
      <h2>辅仁实验幼儿园</h2>
      <h4>--孩子成长的摇篮</h4>
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
  height: 50em;
  background: url("../../../static/img/19-copy1.png") no-repeat fixed;
  background-size: 100% 100%;
  
  .section1 {
    padding:3em 1em 3em 1em;
    // border: 2px solid;
    text-align: center;
    border-radius: 30px;
    align-self: center;
    position: relative;
    top: 10%;
    left: 10%;
    background-color: #ffa100;
    width: 40%;

    h2{
      font-size:3em;
      font-weight: bold;
      color:white;
    }

    h4{
      font-size:1.5em;
      font-weight: bold;
      color:white;
    }
  }
}
</style>
