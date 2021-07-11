<template>
    <nav>
        <v-app-bar app flat class="transparent">
            <span class="white--text">Menu</span><v-app-bar-nav-icon class="white--text"></v-app-bar-nav-icon>
            <v-row justify="center" id="mainLogo" class="mt-1">
                <img id="apexLogoImg" :src="require(`../assets/apexLogoWhite.png`)" alt="">
            </v-row>
            <v-btn text class="white--text">Book Now</v-btn>
        </v-app-bar>
    </nav>
</template>

<script>


export default {
  name: 'Splash',
  components: {
    
  }
}
</script>

<style>

#apexLogoImg {
    width: 50px;
}
    
</style>
