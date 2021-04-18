<template>
  <div id="app">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <NavBar/>
    <CareersPage/>
    <Footer/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import NavBar from './components/NavBar'
import CareersPage from './components/CareersPage'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    NavBar,
    CareersPage,
    Footer
  }
}
</script>

<style>
#app {
  font-family: 'ABeeZee', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
