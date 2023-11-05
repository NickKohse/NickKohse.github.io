<template>
  <Header />
  <footer>More to come...</footer>
</template>

<script>
import Header from './components/Header.vue'


export default {
  name: 'App',
  components: {
    Header,
  },
}
</script>

<style>
#app {
  font-family: 'Trebuchet MS', Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
footer {
  background-color: #57c295;
  position: absolute;
  bottom: 0;
  width: 100%;
}
* {
  margin: 0;
}
</style>
