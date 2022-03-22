<template>
  <TheHeader />
  <TheLogo />
  <TheNavBar />
  <!-- Page Header -->
  <header class="flex flex-col items-center justify-center h-40 py-4">
    <h1 class="text-5xl uppercase md:text-6xl lg:text-7xl">
    </h1>
    <TheFooter />
  </header>
</template>


<script setup>
import TheHeader from "./components/TheHeader.vue";
import TheFooter from "./components/TheFooter.vue";
</script>