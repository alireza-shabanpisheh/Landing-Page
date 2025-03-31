<template>
    <div>
      <button class="bg-black text-white py-4 px-8 rounded-[2.25rem] border-2 border-white">{{ text2 }}</button>
    </div>
  </template>
    
  <script setup lang="ts">
  
      const props = defineProps<{
      text2: string;
      }>();
  
  </script>

<style lang="scss" scoped>

</style>