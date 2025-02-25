<script setup lang="ts">
const route = useRoute()

console.log(route.params.id);
console.log(route.query.type);
console.log(route.query.page);
</script>

<template>
    <h1>User Dynamic Routes And Query</h1>
    <h3>Hello, {{ $route.params.id }}</h3>
    <h3>Type : {{ $route.query.type }}</h3>
    <h3>Page : {{ $route.query.page }}</h3>
</template>

<style scoped>

</style>