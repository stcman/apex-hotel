<template>
  <div class="splash">
    <!-- <v-carousel :show-arrows="false">
        <v-carousel-item
        v-for="(item,i) in items"
        :key="i"
        :src="require(`../assets/hotel1.jpg`)"
        ></v-carousel-item>
    </v-carousel> -->
    <v-img
        :src="require(`../assets/hotel1.jpg`)"
        height="100vh"
        gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)"
        class="grey darken-4"
    ></v-img>


    <div>TEST</div>

  </div>
</template>

<script>


export default {
    name: 'Splash',
    data () {
        return {
        items: [
            {
            src: '/assets/hotel1.jpg',
            },
            {
            src: 'https://cdn.vuetifyjs.com/images/carousel/sky.jpg',
            },
            {
            src: 'https://cdn.vuetifyjs.com/images/carousel/bird.jpg',
            },
            {
            src: 'https://cdn.vuetifyjs.com/images/carousel/planet.jpg',
            },
        ],
        }
    },
  components: {
    
  }
}
</script>

<style>
    /* .splash {
        background-image: url("../assets/hotel1.jpg");
        background-color: #cccccc;
        height: 100vh;
    } */
</style>
