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

   <style>
   h1 {
       width: 100%;
          
    background: rgb(129, 70, 70);
    
    color: rgb(255, 255, 255);
    text-align: center;
   }

   p {
       text-align: center;
       
   }
   </style>