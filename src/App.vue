<template>
  <div id="app">
    <Nav class="app-nav" />
    <Dashboard />
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
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 5px;
}
.app-nav {
  position: sticky;
  top: 0;
}
</style>
