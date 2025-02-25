<script setup lang="ts">
const route = useRoute();

const slug: string[] = ref(route.params.slug);

console.log(route.params.slug)
</script>

<template>
  <div>
    <h1>Backend Catch All Routes Page</h1>
    <div v-if="$route.params.slug">
      <p>Backend: {{ $route.params.slug }}</p>
      <p v-for="item in slug" :key="item">{{ item }}</p>
    </div>
    <p v-else>Backend Not Found</p>
  </div>
</template>

<style scoped>

</style>
