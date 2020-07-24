<template>
  <div class="nav-element-container2">
    <div class="nav-element-label">
      {{navItem}}
    </div>
  </div>
</template>

<script>
export default {
  name: 'NavElement',
  props: {
    'navItem': {
      type: String,
      required: true,
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.nav-element-container2 {
  border-color: white;
  border-style:hidden;
  height: 4rem;
  float: left;
  width: 100%
}
.nav-element-label {
  float: left;
}
h1 {
  font-size: 1rem;
}
</style>
