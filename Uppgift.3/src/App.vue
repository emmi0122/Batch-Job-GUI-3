<template>
  <Sidebar />
  <Header />
</template>

<script setup>
import Header from "./components/Header.vue";
import Sidebar from "./components/Sidebar.vue";
</script>

<style>
body {
  margin: 0;
  font-family: "Inter", sans-serif;
}

#app {
  display: flex;
}
</style>
