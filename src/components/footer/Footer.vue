<template>
  <div class="footer-container">
    <div class="footer-icons">
      <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
      <i class="fa fa-github" aria-hidden="true"></i>
      <i class="fa fa-facebook-square" aria-hidden="true"></i>
      <i class="fa fa-instagram" aria-hidden="true"></i>
      <i class="fa fa-twitter" aria-hidden="true"></i>

    </div>
    <div class="footer-license">
      Released under the MIT License
      Copyright © 2020 Jacob Burton
    </div>
  </div>
</template>

<script>
export default {
  name: 'Footer',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.footer-container {
  color: white;
  background-color: dimgrey;
  height: 7rem;
}
.footer-icons {
  padding-top: 2rem;
}
.footer-license {
  padding-top: 1rem;
  padding-bottom: 2rem;
}
.fa {
  padding-right: 1rem;
  padding-left: 1rem;
}
h1 {
  font-size: 2rem;
}

</style>
