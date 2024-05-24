<script setup>
import Card from "./Card.vue";
</script>
<template>
  <div class="content-back-wrapper">
    <div class="content-wrapper">
      <Card />
    </div>
  </div>
</template>
<style scoped>
.content-back-wrapper {
  background-color: #fff;
}

.content-wrapper {
  width: 100%;
  min-height: 100vh;
  padding: 50px;
  background-image: url("../assets/pattern.png");
  background-size: 428px;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
