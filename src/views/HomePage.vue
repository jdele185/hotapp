<script setup>
import { ref } from 'vue'
const title = ref('Desired Route 🗺️')
</script>

<template>
  <main class="flex min-h-screen items-center justify-center">
    <h1 class="text-6xl font-thin text-slate-800">{{ title }}</h1>
    <form class="destination-form" @submit="destinations">
      <input type="text" placeholder="Destination" />
      <button type="submit" class="bg-blue-400 px-2 py-2" @click="destinations">Destination</button>
    </form>
  </main>
</template>

