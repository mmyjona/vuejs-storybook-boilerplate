<template>
  <div id="app">
    <img src="./assets/logo.png">
    <hello></hello>
    <hello3></hello3>
  </div>
</template>

<script>
import Hello from './components/Hello.vue'
import Hello3 from './components/Hello3.vue'

export default {
  name: 'app',
  components: {
    Hello,
    Hello3
  }
}
</script>

<style lang='less'>

@import "../vendors/iview/src/styles/index.less";

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
