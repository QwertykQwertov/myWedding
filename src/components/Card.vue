<template>
  <div class="card-wrapper">
    <h2>Дорогой гость!</h2>
    <p>
      Мы рады сообщить Вам, что <span>10.08.2024</span> состоится самое главное
      торжество в нашей жизни - <span>день нашей свадьбы!</span> Приглашаем Вас
      разделить с нами радость этого незабываемого дня.
    </p>
    <h3>Ждем Вас!</h3>
    <div class="card-photo">
      <img src="../assets/2e501a.jpg" alt="" />
    </div>
    <h3>Ваши <br />Иван и Екатерина</h3>
  </div>
</template>
<style scoped>
.card-wrapper {
  width: 79%;
  padding: 20px;
  height: auto;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  max-width: 700px;
  background-color: rgba(255, 255, 255, 0.7);
  border-radius: 10px;
}

.card-photo {
  width: 70%;
  border-radius: 50%;
  overflow: hidden;
}

img {
  width: 100%;
}

h2 {
  font-family: SaintAmour;
  font-size: 8em;
  margin: 0;
}
h3 {
  font-family: SaintAmour;
  font-size: 5em;
  margin: 0;
}
p {
  margin: 0;
  font-family: Cormorant;
  font-size: 1.5em;
}
span {
  color: #c6a08b;
}
@media (max-width: 600px) {
  h2 {
  font-family: SaintAmour;
  font-size: 5em;
  margin: 0;
}
h3 {
  font-family: SaintAmour;
  font-size: 4em;
  margin: 0;
}
p {
  margin: 0;
  font-family: Cormorant;
  font-size: 1.2em;
}
}
</style>
