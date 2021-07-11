<template>
  <div class="home">
    <Navbar />
    <Splash />
  </div>
</template>

<script>
  import Navbar from '../components/Navbar.vue';
  import Splash from '../components/Splash.vue';

  export default {
    name: 'Home',

    components: {
      Navbar,
      Splash,
    },
  }
</script>
