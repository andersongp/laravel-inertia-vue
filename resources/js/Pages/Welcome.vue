<template>
    <h1>Seja bem vindo {{ nome }}</h1>
</template>

<script setup>
import { ref } from 'vue';

const nome = ref("teste");
</script>