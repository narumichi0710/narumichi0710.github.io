<template>
  <div> <!-- <div id="app"> -->
    <Header></Header>
    <About></About>
    <Skills></Skills>
    <Works></Works>
    <Footer></Footer>
    <!-- <div id="nav"> -->
      <!-- <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> -->
    <!-- </div> -->
    <!-- <router-view/> -->
  </div>
</template>

<script>

import Header from './components/pages/Header'
import About from './components/pages/About'
import Skills from './components/pages/Skills'
import Works from './components/pages/Works'
import Footer from './components/pages/Footer'
export default {
  components: {
    Header,
    About,
    Skills,
    Works,
    Footer,
  },
}
</script>

<style>
.vue-typer .custom.char{
  color: rgb(80, 80, 80);
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
}
#nav a {
  font-weight: bold;
  color: #2c3e50;
}
#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
