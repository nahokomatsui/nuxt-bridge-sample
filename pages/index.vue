<template>
  <div>
    {{ message }}
    <Tutorial/>
  </div>
</template>

<script lang="ts">
import { defineComponent, ref } from '#imports'

export default defineComponent({
  setup() {
    const message = ref('hi!');

    return {
      message
    }
  }
})
</script>
