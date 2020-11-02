<template>
  <v-app id="app" style="margin-top: 0px !important">
      <Introduction />
    <!-- <AboutMe /> -->
      <Socials />
  </v-app>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import AboutMe from './components/AboutMe/index.vue'
import Introduction from './components/Introduction/index.vue'
import Socials from './components/Socials/index.vue'


export default {
  name: 'App',
  components: {
    // HelloWorld
    // AboutMe,
    Introduction,
    Socials,
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
  background-color: rgba(0, 24, 68)
}
</style>
