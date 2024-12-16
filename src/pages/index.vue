<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>

<template>
  <div>
    <h1>Welcome to Vuejs Masterclass 2024</h1>
    <p>This is the home page.</p>
    <RouterLink :to="{ path: '/projects/1' }">View Projects</RouterLink>
  </div>
</template>

