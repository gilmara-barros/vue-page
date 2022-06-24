<template>
  <!--<img alt="Vue logo" src="./assets/logo.png">-->
  <Pagination-Projects msg="Projetos"/>
</template>

<script>
import Pagination-Projects from './components/Pagination-Projects.vue'

export default {
  name: 'App2',
  components: {
    Pagination-Projects
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
