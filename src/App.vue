<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router';
import MainLayout from './layouts/MainLayout.vue';
</script>

<template>
  <header>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
  </header>
<MainLayout>
  <RouterView />
</MainLayout>
</template>

<style scoped>
</style>
