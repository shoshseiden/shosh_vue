<template>
  <div id="app">
    <ShoshVue/>
  </div>
</template>

<script>
import ShoshVue from './components/ShoshVue.vue'

export default {
  name: 'app',
  components: {
    ShoshVue
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
