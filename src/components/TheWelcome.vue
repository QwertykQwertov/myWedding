<template>
  <div class="welcome">
    <p class="textLine">Екатерина</p>
    <p class="text-middle"><span>_____</span> AND <span>_____</span></p>
    <p class="textLine" style="">Иван</p>
    <div class="element1"></div>
  </div>
</template>

<style scoped>
.welcome {
  display: flex;
  flex-direction: column;
  align-items: center;
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
  margin-top: -50px;
  height: 500px;
  width: 100%;
  background-image: url("../assets/kitty.png");
  background-position: top;
  background-repeat: no-repeat;
  background-size: contain;
}
</style>
