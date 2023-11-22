<script setup lang="ts">

</script>

<template>
  <header class="flex flex-row p-16">
    <nav class="flex flex-row gap-4 justify-between w-full px-40">
      <NuxtLink to="/">
        <div class="bg-black p-3 text-white w-40 text-center">
          Accueil
        </div>
      </NuxtLink>
      <NuxtLink to="/cv">
        <div class="bg-black p-3 text-white w-40 text-center">
          Mon CV
        </div>
      </NuxtLink>
      <NuxtLink to="/projets">
        <div class="bg-black p-3 text-white w-40 text-center">
          Mes projets
        </div>
      </NuxtLink>
      <NuxtLink to="/a-propos">
        <div class="bg-black p-3 text-white w-40 text-center">
          À propos
        </div>
      </NuxtLink>
      <NuxtLink to="/contact">
        <div class="bg-black p-3 text-white w-40 text-center">
          Contact
        </div>
      </NuxtLink>
    </nav>
  </header>
</template>

<style scoped>

</style>