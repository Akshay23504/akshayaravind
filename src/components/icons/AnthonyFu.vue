<script setup lang="ts">
const props = defineProps<{ class?: string }>()
</script>

<template>
  <div v-if="props.class" :class="props.class" class="i-simple-icons:antfu" />
  <div v-else class="i-simple-icons:antfu" />
</template>
