<template>
  <div id="app">
    <Timer msg="This is My TIMER"/>
  </div>
</template>

<script>
  import Timer from './components/Timer.vue'

  export default {
    name: 'app',
    components: {
      Timer
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
    margin-top: 10px;
  }
</style>
