<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Essential Links</h2>
    <ul>
      <li><a href="https://vuejs.org" target="_blank">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank">Forum</a></li>
      <li><a href="https://gitter.im/vuejs/vue" target="_blank">Gitter Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank">Twitter</a></li>
      <br>
      <li><a href="http://vuejs-templates.github.io/webpack/" target="_blank">Docs for This Template</a></li>
    </ul>
    <h2>Ecosystem</h2>
    <ul>
      <li><a href="http://router.vuejs.org/" target="_blank">vue-router</a></li>
      <li><a href="http://vuex.vuejs.org/" target="_blank">vuex</a></li>
      <li><a href="http://vue-loader.vuejs.org/" target="_blank">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank">awesome-vue</a></li>
    </ul>
    <i-button>Default</i-button>
    <i-button type="primary">Primary</i-button>
    <i-button type="ghost">Ghost</i-button>
    <i-button type="dashed">Dashed</i-button>
    <i-button type="text">Text</i-button>
    <br><br>
    <i-button type="info">信息按钮</i-button>
    <i-button type="success">成功按钮</i-button>
    <i-button type="warning">警告按钮</i-button>
  </div>
</template>

<script>
import Button from '../../vendors/iview/src/components/button';

export default {
  name: 'hello',
  components:{'i-button':Button},
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang='less'>
@import (reference) "../../vendors/iview/src/styles/index.less";
@import "../../vendors/iview/src/styles/components/button.less";

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
