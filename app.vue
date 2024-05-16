<template>
  <div class="w-100 h-100 top-0 right-0 left-0 right-0">
    <j-header />
    <info-half />
    <content-half />
    <j-footer />
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