<script setup lang="ts">
import { useRoute } from 'vue-router'

const routes = useRoute();
</script>

<template>
  <p>This is project {{ routes.params?.id }}</p>
</template>
