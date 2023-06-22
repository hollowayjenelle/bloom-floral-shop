<template>
  <div class="parent-container">
    <div class="content-container about-section">
      <h1 class="about-title">Who are we?</h1>
      <div class="about-content">
        <p class="about-paragraph">
          At Bloom, we're passionate about the transformative power of flowers.
          Our skilled florists curate vibrant arrangements, capturing the
          essence of every occasion. With exceptional quality and personalized
          service, Bloom is your trusted destination for stunning floral designs
          that truly bloom with love and artistry.
        </p>
        <img src="../assets/about-section-img.jpg" alt="" class="about-img" />
      </div>
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped>
.about-title {
  color: #283618;
  font-size: 48px;
  font-family: "Poppins", serif;
  font-weight: 600;
  text-align: center;
}

.about-content {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.about-paragraph {
  color: #283618;
  font-size: 32px;
  font-family: "Poppins", serif;
}

.about-img {
  width: 402px;
  height: 586px;
  border-radius: 8px;
  box-shadow: 10px 15px 4px 0px rgba(221, 161, 94, 0.75);
}
</style>
