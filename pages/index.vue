<script lang="ts" setup>
useHead({
  title: 'Home',
  meta: [
    {
      name: 'description',
      content:
        'Selamat datang di sunnycodes. Temukan jasa pembutan, artikel dan unduh kode sumber aplikasi web yang modern dengan nuxt.js framework yang menguntungkan.',
    },
  ],
  titleTemplate: 'sunnycodes\'s Blog - %s',
})

// Generate OG Image
defineOgImageComponent('About', {
  headline: 'Salam',
  title: 'sunnycodes\'s Blog',
  description: 'Selamat datang di sunnycodes. Temukan jasa pembutan, artikel dan unduh kode sumber aplikasi web yang modern dengan nuxt.js framework yang menguntungkan.',
  link: '/sunnycodes.jpg',
})
</script>

<template>
  <main class="container max-w-5xl mx-auto text-zinc-600">
    <MainHero />
    <MainRecent />
    <MainTrending />
  </main>
</template>
