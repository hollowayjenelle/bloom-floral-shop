<template>
  <div class="home-banner">
    <NavigationBar :isHome="true" />
  </div>
</template>

<script setup lang="ts">
import NavigationBar from "./NavigationBar.vue";
</script>

<style scoped>
.home-banner {
  background-image: url("../assets/home-banner-img.jpg");
  background-size: cover;
  height: 960px;
  padding-top: 40px;
}

.home-banner-text {
  color: #000;
  text-align: center;
  font-size: 64px;
  font-family: "Poppins", sans-serif;
  font-weight: 700;
}
</style>
