<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <MyTestVueComponent /> <!-- Now it's being used -->
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import MyTestVueComponent from './components/MyTestVueComponent.vue'; // Corrected import

export default {
  name: 'App',
  components: {
    MyTestVueComponent
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
