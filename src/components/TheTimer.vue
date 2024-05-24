<script setup>
const wedDay = new Date("2024-08-10");
const today = new Date();

const diffDays = Math.floor((wedDay - today) / (1000 * 60 * 60 * 24));
</script>

<template>
  <div class="timer">
    <h2>
      Дней до мероприятия: <span>{{ diffDays }}</span>
    </h2>
  </div>
</template>

<style scoped>
.timer {
  font-family: Cormorant;
}
.timer span {
  font-family: cursive;
  font-size: 1.2em;
}
</style>
