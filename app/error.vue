<script setup>
import { onMounted } from 'vue'

const redirectUrl = 'https://linkbudd.com/eiotclub' // <-- Your desired URL

onMounted(() => {
  window.location.href = redirectUrl
})
</script>

<template>
  <div class="flex items-center justify-center min-h-screen">
    <p>Redirecting...</p>
  </div>
</template>
