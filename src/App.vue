<!-- Composant parent -->
<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="My application VueJS"/>
</template>

<script>
// Import des composants
import HelloWorld from './components/HelloWorld.vue'

// Charhement des composants
export default {
  name: 'App',
  components: {
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
