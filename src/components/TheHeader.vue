<template>
  <header>
    <h1>{{ props.title }}</h1>
    <p>{{ props.description }}</p>
    </header>
</template>

<script setup>
   import {defineProps} from 'vue';
   const props = defineProps({
     title:{
       type: String,
       default:'Default Text'
     },
     description:{
       type: String,
       default: 'A simple description'
     }
   });
   </script>
   