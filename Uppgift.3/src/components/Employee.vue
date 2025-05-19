<template>
    <div class="employee-card" v-for="(em, index) in employeeNames" :key="index">
        <img src="../assets/profile-picture.webp" alt="Profile-picture">
        <div class="employee-info">
            <h4>{{ em }}</h4>
            <p>{{ employeeProfessions[index] }}</p>
        </div>
    </div>
</template>

<script setup>
const employeeNames = ["Albert Svensson", "Doris Johnson", "Moa Haag", "Stefan Holm", "Fatima Diame", "Harrison Ford", "Daniel García", "Joanna Rudzki", "David Lynch", "Anders Ofvegard"]
const employeeProfessions = ["Elektriker, Murare, Snickare, VVS", "Snickare", "Elektriker", "Elektriker, VVS", "Murare", "Snickare", "Målare", "Murare, Målare", "Målare", "Arg snickare"]
</script>

<style scoped>
img {
    width: 3rem;
}

.employee-card {
    width: 10rem;
    border: solid black;
    display: flex;
    align-items: center;
}

.employee-info h4 {
    margin: 0;
    font-size: small;
}

.employee-info p {
    margin: 0;
    font-size: smaller;
    display: flex;
}
</style>