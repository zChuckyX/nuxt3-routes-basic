<script setup lang="ts">
import '@/assets/css/app.css';
</script>

<template>
  <main>
    <div class="menu">
      <ul>
        <li><nuxtLink to="/">Home</nuxtLink></li>
        <li><nuxtLink to="/about">About</nuxtLink></li>
        <li><nuxtLink to="/contact">Contact</nuxtLink></li>
        <li><nuxtLink to="/users/garfield?type=admin&page=1">/users/garfield?type=admin&page=1</nuxtLink></li>
        <li><nuxtLink to="/members/admins/garfield">/members/admins/garfield</nuxtLink></li>
        <li><nuxtLink to="/category/milk">/category/milk</nuxtLink></li>
        <li><nuxtLink to="/backend/Typescript/Javascript/Nuxt/Vue">/backend/Typescript/Javascript/Nuxt/Vue</nuxtLink></li>
        <li><nuxtLink to="/parent/child">/parent/child</nuxtLink></li>
        <li><nuxtLink to="/parent/sister">/parent/sister</nuxtLink></li>
      </ul>
    </div>
    <div class="content">
      <NuxtPage />
    </div>
  </main>
</template>
