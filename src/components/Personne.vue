<script setup>
import { ref } from "vue";
const nom = ref("Mohamed");
const age = ref(22);
</script>
<template>
<div>
<h1>Welcome</h1>
<h3>Je m'appelle {{ nom }} </h3>
<div class="item"> j'ai {{age}} ans </div>
</div>
</template>
<style scoped>
h3{
font-weight: 500;
font-size: 2.6rem;
position: relative;
top: -10px;
}
.item {
margin-top: 2rem;
font-size: 20px;
font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
font-style: italic;
}
</style>