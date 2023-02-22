<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Nick Kohse"/>
  <a href="https://github.com/NickKohse">GitHub</a>
  <br/>
  <a href="nick-resume.pdf" download>Resume</a>
  <footer>More to come...</footer>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
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
footer {
  background-color: #57c295;
  position: absolute;
  bottom: 0;
  width: 99.5%;
}
</style>
