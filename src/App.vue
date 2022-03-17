<template>
  <div>
    <TheHeader :title = "pageHeader"  :description = "pageDescription" />
    <main>
      <p>This is on the home page</p>
      </main>
      <TheFooter />
  </div>
</template>

<script setup>
import TheHeader from './components/TheHeader.vue';
import TheFooter from './components/TheFooter.vue';
const pageHeader = 'HomePage!';
const pageDescription = 'This is the landing page for website';

</script>

<style>
   #app {
       background-color:palevioletred;
       text-align: center;
   }
   </style>