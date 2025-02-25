<script setup lang="ts">
const route = useRoute();

console.log(route.params.slug);

</script>

<template>
  <div>
    <h1>Category Dynamic Routes (Optional) Page</h1>
    <h3 v-if="$route.params.slug">slug: {{ $route.params.slug }}</h3>
    <h3 v-else>Category Not Found</h3>
  </div>
</template>

<style scoped>

</style>
