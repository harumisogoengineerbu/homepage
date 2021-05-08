<template>
  <Header/>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <Startsite/>
  <Black/>
  <Foods/>
  <Black/>
  <Cultures/>
  <Footer/>
</template>

<script>
  import Header from './components/Header.vue'
  import HelloWorld from './components/HelloWorld.vue'
  import Startsite from './components/Startsite.vue'
  import Black from './components/Black.vue'
  import Foods from './components/Foods.vue'
  import Cultures from './components/Cultures.vue'
  import Footer from './components/Footer.vue'

  export default {
    name: 'App',
    components: {
      Header,
      HelloWorld,
      Startsite,
      Black,
      Foods,
      Cultures,
      Footer
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
  }
</style>
