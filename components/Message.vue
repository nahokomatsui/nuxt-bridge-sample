<script setup lang="ts">
defineProps({
  value: {
    type: String,
    required: true
  }
})
</script>

<template>
  <span>
    {{ value }}
  </span>
</template>