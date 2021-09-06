<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Spooky Happenings"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  //anything related to vue goes here
  name: 'App',
  components: {
    //the file that we imporated has been put in here --> we can now start referceing it in our template/site
    HelloWorld
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
