<script setup lang="ts">
const route = useRoute();

console.log(route.params.grop);
console.log(route.params.id);
</script>

<template>
    <h1>Member Group Multi Dynamic Routes Page</h1>
    <p>Group: {{ $route.params.group }}</p>
    <p>id: {{ $route.params.id }}</p>
</template>

<style scoped>

</style>