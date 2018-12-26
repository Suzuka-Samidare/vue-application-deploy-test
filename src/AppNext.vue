<template>
  <div id="app-next">
    <img src="./assets/angular.png">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App2'
}
</script>

<style>
#app-next {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
#app-next img {
  height: 400px;
}
</style>
