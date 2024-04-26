<script setup>
import TheHeader from "./components/TheHeader.vue";
import TheWelcome from "./components/TheWelcome.vue";
// import TheHeader from './components/TheHeader.vue'
</script>

<template>
  <TheHeader />
  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>
main {
  background: rgb(255, 255, 255);
}
</style>
