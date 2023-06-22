<template>
  <div class="navigation-bar">
    <h1 class="company-name">Bloom</h1>
    <div class="navigation-links">
      <a href="">About</a>
      <a href="">Catalog</a>
      <a href="">Reviews</a>
      <a href="">Contact</a>
    </div>
    <button v-if="isHome" class="shop-btn">Shop Now</button>
  </div>
</template>

<script setup lang="ts">
defineProps({
  isHome: Boolean,
});
</script>

<style scoped>
.navigation-bar {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.company-name {
  color: #000;
  font-size: 40px;
  font-family: "Crimson Text", serif;
  letter-spacing: 2.4px;
  text-transform: uppercase;
}

.navigation-links {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  width: 524px;
}

.navigation-links a {
  color: #000;
  font-size: 24px;
  font-family: "Poppins", sans-serif;
  text-decoration: none;
}

.navigation-links a:hover {
  color: white;
  text-decoration: underline;
}

.shop-btn {
  width: 178px;
  height: 58px;
  border-radius: 50px;
  background: #dda15e;
  color: white;
  border: none;
  font-size: 24px;
  font-weight: 600;
}
</style>
