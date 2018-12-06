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
@font-face {
    font-family: 'tahu';
    src: url('./assets/fonts/tahu-webfont.woff2') format('woff2'),
         url('./assets/fonts/tahu-webfont.woff') format('woff');
    font-weight: normal;
    font-style: normal;
}

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
