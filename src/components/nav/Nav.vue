<template>
  <div class="nav-container">
      <div class="nav-element-container" v-for="(value, index) in navItems"
        :key="index">
        <NavElement :navItem="value" />
      </div>
  </div>
</template>

<script>
import NavElement from './NavElement.vue'
export default {
  name: 'Nav',
  data: () => {
    return {
      navItems: ['about', 'contact', 'teams']
    }
  },
  components: {
    NavElement
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.nav-container {
  background-color: #6bc29b;
  width: 100%;
  height: 4rem;
}
.nav-element-container {
  /* padding-right: 1.5rem; */
  float: right;
  /* display: inline-block; */
  width: 10%; 
  text-align: center;
}
h1 {
  font-size: 1rem;
}
</style>
