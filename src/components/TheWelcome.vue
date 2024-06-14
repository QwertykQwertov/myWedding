<script setup>
import TheTimer from "./TheTimer.vue";
</script>

<template>
  <div class="welcome">
    <p class="textLine animate-slide-left">Иван</p>
    <p class="text-middle animate-opacity">
      <span>_____</span> AND <span>_____</span>
    </p>
    <p class="textLine animate-slide-right" style="">Екатерина</p>
    <div class="element1 animate-zoom-in"></div>
    <div class="welcome-text animate-opacity">
      <h3>10 августа 2024</h3>
      <p>Приглашают разделить этот день с ними</p>
    </div>
    <TheTimer />
  </div>
</template>

<style scoped>
.welcome {
  display: flex;
  flex-direction: column;
  align-items: center;
  height: 100%;
}
.textLine {
  font-size: 72.7984pt;
  font-family: SaintAmour;
  color: rgb(204, 156, 132);
  line-height: inherit;
  text-align: center;
}

p {
  margin: 0;
}

.text-middle {
  margin: -34px 0;
  color: black;
  font-family: Cormorant;
  font-size: 10.2774pt;
}

span {
  vertical-align: super;
  color: rgb(204, 156, 132);
}

.element1 {
  flex: 1;
  margin-top: -50px;
  height: 500px;
  width: 100%;
  background-image: url("../assets/kitty-cut.png");
  background-position: 50%;
  background-repeat: no-repeat;
  background-size: contain;
  top: 18.5%;
}

.welcome-text {
  text-align: center;
  font-family: Cormorant;
  font-size: 1.5em;
  margin-top: 10px;
}
h3 {
  margin: 0;
}

/* animations */
.animate-slide-left {
  animation: slideLeft 1.5s ease forwards;
}

.animate-slide-right {
  animation: slideRight 1.5s ease forwards;
}

.animate-opacity {
  animation: opacity 1.5s ease forwards;
}
.animate-zoom-in {
  animation: zoomIn 1.5s ease forwards;
}

/* keyframes */
@keyframes slideLeft {
  0% {
    transform: translateX(500px);
    opacity: 0;
  }

  100% {
    transform: translateX(0);
    opacity: 1;
  }
}

@keyframes slideRight {
  0% {
    transform: translateX(-500px);
    opacity: 0;
  }

  100% {
    transform: translateX(0);
    opacity: 1;
  }
}

@keyframes opacity {
  0% {
    opacity: 0;
  }

  100% {
    opacity: 1;
  }
}

@keyframes zoomIn {
  0% {
    transform: scale(0);
    opacity: 0;
  }
  80% {
    transform: scale(1.1);
    opacity: 1;
  }

  100% {
    transform: scale(1);
    opacity: 1;
  }
}
</style>
