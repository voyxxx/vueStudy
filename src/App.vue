<template>
  <div id="app">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <basicComponent titl="My journey with Vue"/>
    <basicComponent title="My journey with Vue"/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import basicComponent from './components/basicComponent.vue'


export default {
  name: 'app',
  components: {
    // HelloWorld,
    basicComponent,
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
