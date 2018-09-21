<template>
  <div id="app">
      <List />
      <div class='test'>test TEXT</div>
  </div>
</template>

<script>
  import 'common/css/reset.css';
  import List from 'components/list';
  export default {
    name: 'app',
    components: {
      List
    }
  }
</script>
<style lang="less">
  @import '../common/less/common.less';
  .test{
    color: @BASECOLOR
  }
  .test2{
    color: @COLORTWO
  }
</style>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>
