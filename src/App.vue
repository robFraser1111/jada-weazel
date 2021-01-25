<template>
  <ComingSoon msg="Coming soon"/>
</template>

<script>
import ComingSoon from './components/ComingSoon.vue'

export default {
  name: 'App',
  components: {
    ComingSoon
  }
}
</script>

<style>
html {
  background: black;
}

#app {
  display: grid;
  justify-content: center;
  align-content: center;
  height: 100vw;
  font-family: Lato, Helvetica, Arial, sans-serif;
  text-align: center;
  color: white;
}
</style>
