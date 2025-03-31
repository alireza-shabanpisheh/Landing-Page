<template>
  <div>
    <button class="bg-gradient-to-r from-[#8C01FA] to-[#000000] text-white py-4 px-8 rounded-[2.25rem] border-2 border-black">{{text}}</button>
  </div>
</template>
  
<script setup lang="ts">

    const props = defineProps<{
    text: string;
    }>();

</script>
  


<style lang="scss" scoped>
</style>