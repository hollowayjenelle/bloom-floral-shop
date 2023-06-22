<template>
  <div class="parent-container catalog-parent">
    <div class="content-container catalog-container">
      <div class="catalog-option">
        <img src="../assets/pre-arranged.jpg" alt="" class="catalog-pic" />
        <p class="catalog-text">
          Shop for pre-arranged <br />
          bouquets
        </p>
        <button class="shop-now-btn">Shop Now</button>
      </div>
      <div class="catalog-option">
        <img src="../assets/custom-bouquet.jpg" alt="" class="catalog-pic" />
        <p class="catalog-text">
          Create your <br />
          own bouquet
        </p>
        <button class="shop-now-btn">Shop Now</button>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped>
.catalog-parent {
  background: #dda15e;
}

.catalog-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 100px 0;
}

.catalog-option {
  width: 538px;
  display: flex;
  flex-direction: column;
  border: 2px solid #283618;
  border-radius: 8px;
  padding-bottom: 30px;
}

.catalog-pic {
  width: 100%;
  height: 596px;
  border-radius: 8px;
}

.catalog-text,
.shop-now-btn {
  color: #283618;
  text-align: center;
  font-size: 40px;
  font-family: "Poppins", sans-serif;
  font-weight: 600;
  margin-top: 35px;
}

.shop-now-btn {
  width: 294px;
  height: 106px;
  border-radius: 50px;
  border: 4px solid #283618;
  background: transparent;
}
</style>
