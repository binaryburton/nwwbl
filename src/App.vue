<template>
  <div id="app">
    <Nav />
    <Dashboard class="dash" />
    <Footer />
  </div>
</template>

<script>
import Dashboard from './components/Dashboard.vue'
import Nav from './components/nav/Nav.vue'
import Footer from './components/footer/Footer.vue'

export default {
  name: 'App',
  components: {
    Nav,
    Dashboard,
    Footer
  }
}
</script>

<style>
.dash {
  border-style: solid;
  border-color: #6bc29b;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 10px;
}
</style>
