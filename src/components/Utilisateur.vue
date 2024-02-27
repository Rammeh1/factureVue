<script setup>
import { ref } from "vue";
const user = ref({
  email: "IIT2024@gmail.com",
  adresse: "Campus Elons",
});
</script>
<template>
  <div>
    <h1>{{ user.email }}</h1>
    <h3>Adresse: {{ user.adresse }}</h3>
  </div>
</template>
<style scoped></style>
