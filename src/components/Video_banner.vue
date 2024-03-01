<template>
  <div class="image-container">
    <video autoplay muted loop src="/public/Videos/Banner.mp4"></video>
    <div class="image-text">
      <h1>Tiago Coradini</h1>
      <h3>Capturando a essência do real</h3>
    </div>
  </div>
</template>

<script>
export default {
  name: "Video_banner",
};
</script>

<style scoped>
video {
  width: 100%;
  filter: grayscale(2);
}

.image-container {
  position: relative;
}

.image-text {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: 1;
  color: white;
  text-align: center;
}
</style>