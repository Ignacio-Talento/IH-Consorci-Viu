<script setup>
    const userNames = ['Juan', 'Pedro', 'Maria', 'Jose', 'Ana'];
</script>

<template>
    <p v-for="(name, index) in userNames" :key="index">
        {{index}} - {{ name }}
    </p>
</template>

<style></style>