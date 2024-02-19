<template>
  <body>
    <Header />
    <main> More to come</main>
    <Footer />
  </body>
</template>

<script>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'


export default {
  name: 'App',
  components: {
    Header,
    Footer,
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
body {
  display: flex;
  flex-direction: column;
  min-height: 100dvh;
}
main {
  color: #2c3e50;
  background-color: #bdc1d8;
  flex: 1;
  padding: 15px;
}
* {
  margin: 0;
}
</style>
