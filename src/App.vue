<template>
  <div id="app">
    <!-- <img src="./assets/logo.png" class="hidden"> -->
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.fade-enter-active {
  transition: opacity .8s;
}
.fade-enter, .fade-leave-to {
  opacity: 0;
}
</style>
