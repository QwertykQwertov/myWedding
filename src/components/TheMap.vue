<script setup>
const mapHeight = document.documentElement.clientWidth > 650 ? 700 : 450;
</script>
<template>
  <div class="map-wrapper">
    <iframe
      src="https://yandex.ru/map-widget/v1/?um=constructor%3Aaf6b0eee04f0e9a6df91e2f21556cdb45de1456495da7ebe77b0889efd9f2006&amp;source=constructor"
      width="100%"
      :height="mapHeight"
      frameborder="0"
    ></iframe>
  </div>
</template>

<style scoped>
.map-wrapper {
  padding: 20px 0;
}
</style>
