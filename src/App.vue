<template>
  <Header />
  <About />
</template>

<script>
import Header from './components/Header.vue'
import About from './components/About.vue'

export default {components : { Header, About } }
</script>

<style>
#app {
  display: block;
  justify-content: center;
  min-height: 100vh;
}

body{
  background-color: white;
  margin: 0;
}
</style>
