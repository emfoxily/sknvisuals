<template>
  <div id="app">
   <Home />
  </div>
</template>

<script>
import Home from './home/Home.vue';

export default {
  name: 'app',
  components: {
    Home,
  },
};
</script>

<style>
body {
  background-image: url('./assets/woodbg.png');
  background-color: #0C7489;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
