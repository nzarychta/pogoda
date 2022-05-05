<template>
  <!--<HelloWorld msg="Welcome to Your Vue.js App"/>-->
  <WeatherView/>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'//
import WeatherView from './components/WeatherView.vue'

export default {
  name: 'App',
  components: {
    //HelloWorld,
    WeatherView
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
