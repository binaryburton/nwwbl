<template>
  <div>
    <div class="dash-container">
      <div class="dash-col">
        <img alt="Vue logo" src="../assets/logo.png">
      </div>
      <div class="dash-col">
        <h1>A Competative Adult Baseball League</h1>
      </div>
    </div>
    <div class="dash-content">
      DASHBOARD CONTENT
    </div>
  </div>
</template>

<script>
export default {
  name: 'Dashboard',
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.dash-container {
  
  padding-top: 1rem;
  display: flex;
  flex-direction: row;
}

.dash-col {
  width: 50%;
  height: 12rem;
}

.dash-content {
  margin-top: 1rem;
  width: 100%;
  height: 22rem;
  background-color: #6bc29b;
}

img {
  padding-right: .5rem;
  float: right;
  width: 7rem;
  height: 12rem;
}
h1 {
  padding-left: .5rem;
  font-size: 1.5rem;
  width: 10rem;
  text-align: left;
}
</style>
