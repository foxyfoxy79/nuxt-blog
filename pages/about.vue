<script setup lang="ts">
defineOgImageComponent('About', {
  headline: 'Salam‘‹',
  title: 'sunsetcodes\'s Blog',
  description: 'Selamat datang di sunsetcodes. Temukan jasa pembutan, artikel dan unduh kode sumber aplikasi web yang modern dengan nuxt.js framework yang menguntungkan.',
  link: '/sunnycodes.jpg',
})
</script>

<template>
  <div class="py-5">
    <div class="sm:grid grid-cols-8 px-6 py-5 sm:py-9 gap-5 container max-w-5xl  mx-auto">
      <div class="col-span-5  max-w-md">
        <div class="flex justify-between">
          <div>
            <h1 class="text-xl sm:text-4xl  pb-2 font-bold ">
              sunsetcodes
            </h1>

            <div class="my-3 space-x-2 md:space-x-3 pb-10">
              <NuxtLink
                to="https://github.com/foxyfoxy79"
                target="_blank"
                class="px-2 py-1 lg:px-3 lg:py-2 bg-gray-300 text-gray-800 rounded-md dark:bg-slate-700 dark:text-[#F1F2F4]"
                aria-label="Github"
              >
                <Icon name="fa:github" size="1em" />
              </NuxtLink>
              
              
              
            </div>
          </div>
          <div class="sm:hidden block col-span-3 pb-5 dark:text-[#F1F2F4]">
            <NuxtImg
              src="/sunnycodes.jpg"
              width="125"
              height="115"
              quality="50"
              class="rounded-md"
            />
          </div>
        </div>
        <h3 class="text-base sm:text-3xl font-semibold pb-7 sm:pb-12">
          Pembuat aplikasi web.
        </h3>

        <p>Halo, kami adalah pembuat aplikasi web dengan keahlian menggunakan nuxt.js yang berdomisili di Kalasan, Sleman, DI Yogyakarta. Temukan jasa pembuatan, artikel dan unduh kode sumber aplikasi web yang modern dengan nuxt.js framework yang menguntungkan.</p>
      </div>
      <div class="hidden sm:block col-span-3">
        <NuxtImg
          src="/sunnycodes.jpg"
          width="450"
          height="500"
          quality="50"
          class="rounded-md"
        />
      </div>
    </div>
  </div>
</template>
