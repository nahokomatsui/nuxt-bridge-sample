<script setup lang="ts">
import { ref } from '#imports'
import Message from "~/components/Message.vue"

const msg = ref('hi!');
</script>

<template>
  <div>
    Message:
    <Message :value="msg" />
  </div>
</template>

