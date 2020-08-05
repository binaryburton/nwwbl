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

// const yo = '<div>Hello</div>';
// const yo = '<v-icon>fas fa-search</v-icon>';

export default {
  name: 'Nav',
  data: () => {
    return {
      navItems: ['fa fa-user', 'fa fa-search', 'about', 'contact', 'teams']
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
  background-color: white;
  position: sticky;
  top: 0;
  width: 100%;
  height: 3rem;
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
