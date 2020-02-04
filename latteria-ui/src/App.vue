<template>
  <div id="app">
   
    <router-view />
    <Footer />
  </div>
</template>

<script>
import Footer from './components/Footer'
export default {
  name: 'app',
  components: {
    Footer
  }
}
</script>

<style>
* {
  padding: 0;
  margin: 0;
}

#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.footer {
  position: fixed;
  text-align: center;
  bottom: 0;
}

</style>
