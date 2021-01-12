<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <TButton />
  </div>
</template>

<script>
import TButton from 'vue-lib-test'

export default {
  name: 'App',
  components: {
    TButton
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
