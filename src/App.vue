<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <mioTitolo/>
    <heroJumbotron/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import mioTitolo from './components/mioTitolo.vue'
import heroJumbotron from './components/heroJumbotron.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    mioTitolo,
    heroJumbotron,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
