<template>
  <NuxtRouteAnnouncer />
  <NuxtLoadingIndicator />
  <NuxtPage />
</template>

<script setup lang="ts">
useHead({
  htmlAttrs: {
    lang: 'es'
  },
  titleTemplate: '%s - GOADeveloper',
  link: [
    {
      rel: 'icon',
      type: 'image/vnd.microsoft.icon',
      href: '/favicon.png'
    }
  ]
})
</script>
