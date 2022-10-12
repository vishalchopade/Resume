<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <ResumeProfile msg="Welcome to Your Vue.js App"/>
</template>

<script>
import ResumeProfile from './components/Resume.vue'

export default {
  name: 'App',
  components: {
    ResumeProfile
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
