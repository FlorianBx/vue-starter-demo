<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <nav class="flex gap-4 justify-end mr-4 p-4">
    <RouterLink
      class="bg-blue-400 hover:bg-blue-600 rounded w-24 flex items-center justify-center py-1.5 px-4 text-white"
      to="/"
      >Home</RouterLink
    >
    <RouterLink
      class="bg-blue-400 hover:bg-blue-600 rounded w-24 flex items-center justify-center py-1.5 px-4 text-white"
      to="/about"
      >About</RouterLink
    >
    <RouterLink
      class="bg-blue-400 hover:bg-blue-600 rounded w-24 flex items-center justify-center py-1.5 px-4 text-white"
      to="/user/21"
      >User 21</RouterLink
    >
  </nav>

  <RouterView />
</template>
