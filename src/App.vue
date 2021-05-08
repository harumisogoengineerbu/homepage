<template>
  <Header/>
  <Startsite/>
  <Black/>
  <Introduce/>
  <Black/>
  <Foods/>
  <Black/>
  <Cultures/>
  <Footer/>
</template>

<script>
  import Header from './components/Header.vue'
  import Startsite from './components/Startsite.vue'
  import Black from './components/Black.vue'
  import Introduce from './components/Introduce.vue'
  import Foods from './components/Foods.vue'
  import Cultures from './components/Cultures.vue'
  import Footer from './components/Footer.vue'

  export default {
    name: 'App',
    components: {
      Header,
      Startsite,
      Black,
      Introduce,
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
