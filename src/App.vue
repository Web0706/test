<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/images/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style lang="less">
#app {
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
