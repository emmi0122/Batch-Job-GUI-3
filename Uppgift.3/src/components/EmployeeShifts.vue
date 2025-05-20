
<script setup>
import { ref } from "vue";

const arr = [
  new URL("../assets/grey-square.png", import.meta.url).href,
  new URL("../assets/green-square.png", import.meta.url).href,
  new URL("../assets/green-striped-square.png", import.meta.url).href,
  new URL("../assets/blue-square.png", import.meta.url).href,
];

const index = ref(0);

const nextImage = () => {
  index.value = (index.value + 1) % arr.length;
};
</script>

<template>
  <button @click="nextImage">
    <img :src="arr[index]" alt="image" />
  </button>
</template>

<style scoped>
button {
  all: unset;
}
</style>
