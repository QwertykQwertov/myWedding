<script setup>
import TheTimer from "./TheTimer.vue";
</script>

<template>
  <div class="welcome">
    <p class="textLine">Екатерина</p>
    <p class="text-middle"><span>_____</span> AND <span>_____</span></p>
    <p class="textLine" style="">Иван</p>
    <div class="element1"></div>
    <div class="welcome-text">
      <h3>10 августа 2024</h3>
      <p>Приглашем разделить этот день с нами</p>
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
</style>
