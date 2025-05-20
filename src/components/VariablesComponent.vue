<script setup>
import { ref } from "vue";

const counter = ref(0);
const counter2 = ref(0);
const message = ref("Esto es un mensaje");

setInterval(() => {
  counter.value++;
  console.log(counter.value);
}, 1000);

function changeMsg() {
  message.value = "Mensaje cambiado";
}

function modifyCounter2(number) {
  counter2.value += number;
}
</script>

<template>
  <h2>Counter: {{ counter }}</h2>
  <h2>
    Counter 2: <button @click="modifyCounter2(-1)">-</button>{{ counter2
    }}<button @click="modifyCounter2(1)">+</button>
  </h2>
  <p>{{ message }}</p>
  <button @click="changeMsg">Cambiar Mensaje</button>
</template>

<style></style>
