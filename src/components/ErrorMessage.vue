<script setup lang="ts">
const props = defineProps<{
  message: string
}>()
//setup
</script>

<template>
  <div class="rounded-lg bg-red-100 p-4 text-red-700">
    <p class="font-semibold">Search Result</p>
    <p>{{ props.message }}</p>
  </div>
</template>
