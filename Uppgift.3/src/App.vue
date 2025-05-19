<template>
  <Sidebar />
  <div><Employee /></div>
</template>

<script setup>
import Sidebar from './components/Sidebar.vue'
import Employee from './components/Employee.vue';
import EmployeeShifts from './components/EmployeeShifts.vue';
</script>

<style>
body {
  margin: 0;
  font-family: 'Inter', sans-serif;
}
</style>
