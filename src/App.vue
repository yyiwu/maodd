<template>
<!--  <img alt="Vue logo" src="./assets/logo.png">-->
<!--  <HelloWorld msg="Welcome to Your Vue.js App"/>-->
  <LoginIndex style="width:30%;margin-top:15%;margin-left:30%"></LoginIndex>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import LoginIndex from './components/LoginIndex.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
    LoginIndex
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
