<template>
  <div>
    <Header />
    <slot />
    <Footer />
  </div>
</template>
<script setup lang="ts">
import { Header } from '.'
import { Footer } from '.';
</script>
<style lang="">
</style>