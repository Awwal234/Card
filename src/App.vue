<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <RouterView />
</template>

<style>
html {
  height: 100%;
}

body,
main {
  min-height: 100vh;
  background-color: hsl(220, 46%, 83%);
}
</style>
