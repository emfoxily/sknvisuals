<template>
  <div class="container">
    <div class="header">
      <div class="logo">
        <img src="../assets/sknvisuals.png" alt="sknvisuals" />
      </div>
      <div class="camera">
        <img src="../assets/cameralens.png" alt="camera lens" />
      </div>
    </div>
    <About />
  </div>
</template>

<script>
  import Navigation from '../navigation/Navigation.vue';
  import About from '../about/About.vue';
  
  export default {
    name: 'Home',
    components: {
      Navigation,
      About
    }
  };
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scope>
  .header {
    background-image: linear-gradient(to top, rgba(255,0,0,0), rgba(25, 25, 25, .5));
    display: flex;
    width: 100%;
    margin: 0 auto;
    top: 0;
    left: 0;
  }
  
  .logo {
    margin-left: 5em;
  }
  
  .logo img {
    width: 135%;
  }
  
  .camera img {
    margin-top: 10px;
    width: 55%;
  }
</style>
