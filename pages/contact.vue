<script setup lang="ts">

</script>

<template>
  <div class="">
    <div class="px-40">
      <h1 class="font-extrabold text-6xl text-center mt-16">Contact</h1>
      <p class="text-center mt-10 text-xl">Contactez-moi si mon profil vous plaît !</p>
    </div>
    <Header />
  </div>
  <div>
    <form>
      <div class="flex flex-col justify-center items-center">
        <label for="name">Nom</label>
        <input type="text" name="name" id="name" placeholder="Votre nom" class="border-2 border-black rounded-md p-2 m-2 w-1/3">
        <label for="email">Email</label>
        <input type="email" name="email" id="email" placeholder="Votre email" class="border-2 border-black rounded-md p-2 m-2 w-1/3">
        <label for="message">Message</label>
        <textarea name="message" id="message" cols="30" rows="10" placeholder="Votre message" class="border-2 border-black rounded-md p-2 m-2 w-1/3"></textarea>
        <button type="submit" class="border-2 border-black rounded-md p-2 m-2">Envoyer</button>
      </div>
    </form>
  </div>
</template>

<style scoped>

</style>