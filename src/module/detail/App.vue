<template>
  <div id="app">
    <img src="./images/logo.png">
    <div>详情内容</div>
    <List />
  </div>
</template>

<script>
  import 'common/css/reset.css';
  import Hello from 'components/Hello/Hello'
  import List from 'components/list'

  export default {
    name: 'app',
    components: {
      Hello,
      List
    }
  }
</script>

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
