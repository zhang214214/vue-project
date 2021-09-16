<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <p class="dd"> 桃 宝 YYDS </p>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
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
.dd {
  font-size:50px;
  color:#ff33cc;
}
</style>
