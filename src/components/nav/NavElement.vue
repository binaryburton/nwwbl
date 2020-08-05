<template>
  <div class="nav-element-container2">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <div v-if="navItem.slice(0,2) === 'fa'">
      <i v-bind:class="navItem" aria-hidden="true"></i>
    </div>
    <div v-else>
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
