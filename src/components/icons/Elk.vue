<script setup lang="ts">
const props = defineProps<{ class?: string }>()
</script>

<template>
  <div v-if="props.class" :class="props.class" class="i-mdi:elk" />
  <div v-else class="i-mdi:elk" />
</template>
