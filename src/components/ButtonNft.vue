<template>
  <div>
    <button class="bg-[#111111] text-white rounded-[1rem] p-4">{{ text3 }}</button>
  </div>
</template>

<script setup lang="ts">
    const props = defineProps<{
    text3: string;
    }>();
</script>


<style lang="scss" scoped>
</style>