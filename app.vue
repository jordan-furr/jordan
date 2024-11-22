<template>
  <div class="h-100vh w-100 pa2 borderbox">
    <NuxtPage />
  </div>
</template>

<script setup lang="ts">
useHead({
  title: 'Jordan Furr',
  meta: [
    { name: 'Jordan Furr', content: 'Jordan Furr' }
  ],
  bodyAttrs: {
    class: 'test'
  }
})
</script>