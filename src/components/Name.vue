<script setup>
import { nameCodes, sex } from "../dictionary";

const params = new URL(document.location).searchParams;
const sxParam =  JSON.parse(params.get("sx"));
const nameParam =  JSON.parse(params.get("nm"));
console.log(params.get("sx"));

let greets = "Дорогой гость!";
if (sxParam && nameParam) {
  greets = `${sex[sxParam]} ${nameCodes[nameParam]}`;
}
</script>
<template>
  <h2>{{ greets }}</h2>
</template>
<style scoped>
@media (max-width: 600px) {
  h2 {
    font-family: SaintAmour;
    font-size: 5em;
    margin: 0;
  }
}
</style>
