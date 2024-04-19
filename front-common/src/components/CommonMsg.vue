<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div>Common Component!! : {{ msg }}</div>
</template>
