<template>
  
  <TheHeader />
  <header class="flex flex-col items-center justify-center h-40 py-4">
    <h1 class="text-5xl uppercase md:text-6xl lg:text-7xl">Main Page</h1>
  </header>

   <BaseSection :title="sectionTitle">
    <template #content>
      <p class="max-w-prose text-xl mx-auto">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias amet saepe porro deserunt
        doloribus, veritatis enim rem suscipit ipsa! Dolore est vero, iusto provident harum vel eos
        itaque veniam iste quas corrupti doloribus molestiae incidunt quia dolores veritatis alias
        quod molestias necessitatibus optio porro, cumque aspernatur expedita. Ea, quasi maxime!
      </p>
    </template>
  </BaseSection>

</template>


<script setup>

import TheHeader from './components/TheHeader.vue';
import BaseSection from './components/BaseSection.vue';

</script>