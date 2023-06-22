<template>
  <div class="home-banner">
    <NavigationBar :isHome="true" />
    <h1 class="home-banner-text">Show them love with Bloom</h1>
  </div>
</template>

<script setup lang="ts">
import NavigationBar from "./NavigationBar.vue";
</script>

<style scoped>
.home-banner {
  background: url("../assets/home-banner-img.jpg"),
    lightgray 50% / cover no-repeat;
}

.home-banner-text {
  color: #000;
  text-align: center;
  font-size: 64px;
  font-family: "Poppins", sans-serif;
  font-weight: 700;
}
</style>
