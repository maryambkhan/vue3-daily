<template>
  <header class="flex gap-4 bg-gray-200 py-4">
    <TheLogo />
    <div class="flex gap-2 items-center ml-2">
      <span class="text-2xl font-semibold text-black">SEPHORA</span>
    </div>
    <div>
      <TheNavBar />
      
      <TheToggle />
    </div>
  </header>
</template>


 <script setup>
import TheLogo from "./TheLogo.vue";
import TheNavBar from "./TheNavBar.vue";
import TheToggle from "./TheToggle.vue";
const title = "Props Day";
</script>