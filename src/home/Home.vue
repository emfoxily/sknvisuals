<template>
  <div class="container">
    <Navigation />
    <div class="logo">
      <img src="../assets/sknvisuals.png" alt="sknvisuals" />
    </div>
    <div class="camera">
      <img src="../assets/cameralens.png" alt="camera lens" />
    </div>
  </div>
</template>

<script>
  import Navigation from '../navigation/Navigation.vue';
  
  export default {
    name: 'Home',
    components: {
      Navigation
    }
  };
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scope>
  .container {
    display: flex;
    width: 90%;
    margin: 100px auto;
  }

  .logo {
    margin-left: 50px;
  }
  
  .logo img {
    width: 150%;
  }
  
  .camera img {
    width: 65%;
  }
</style>
