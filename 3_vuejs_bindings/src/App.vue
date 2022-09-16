<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <Home data="front end team is here" msg="we are friends"/>
  <DataBind/>
  <Child name="anil sidhu"/>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Home from './components/Home.vue'
import DataBind from './components/DataBind.vue'
import Child from './components/Child.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    Home,
    DataBind,
    Child,
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
