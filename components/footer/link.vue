<template>
  <div class="flex flex-col dark:text-zinc-300   my-5 md:my-0 md:justify-self-center">
    <p class="text-black dark:text-zinc-300  text-base font-semibold">
      Quick Link
    </p>
    <NuxtLink to="/" class="hover:underline">
      Home
    </NuxtLink>
    <NuxtLink to="/blogs" class="hover:underline">
      Blog
    </NuxtLink>
    <NuxtLink to="/categories" class="hover:underline">
      Kategori
    </NuxtLink>
    <NuxtLink to="/about" class="hover:underline">
      About
    </NuxtLink>
  </div>
</template>
