<template>
  <div class="main">
    <div class="title flex-col">
      <h1 class="mb-6 animate-pulse">Cat's With Hats Homepage</h1>
      <fxemoji:tophat class="text-7xl animate-bounce"/>
      <fxemoji:cat class="text-9xl"/>
      <h1 class=""></h1>
    </div>
    <div class="space-x-2">
      <a href="https://final.catswithhats.online"><button class="bg-purple-900 text-white py-3 px-3 rounded-full shadow-lg hover:bg-violet-700 focus:outline-none focus:ring-2 focus:ring-purple-400 ">Final</button></a>
      <a href="https://chat.catswithhats.online"><button class="bg-blue-900 text-white py-3 px-3 rounded-full shadow-lg hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-purple-400">Chat App</button></a>
      <a href="https://notes.catswithhats.online"><button class="bg-green-900 text-white py-3 px-3 rounded-full shadow-lg hover:bg-green-700 focus:outline-none focus:ring-2 focus:ring-purple-400">Notes</button></a>
    </div>
  </div>
</template>

<script setup>
  import { useMouse } from '@vueuse/core'

  const { x, y } = useMouse()
</script>

<style lang="postcss">
  .main {
    @apply flex flex-col items-center justify-center min-h-screen space-x-4 text-6xl text-coolGray-300 font-extralight;
  }
  .title {
    @apply flex items-center justify-center;
  }
</style>
