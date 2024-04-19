<script setup>
import { CommonMsg } from 'front-common'
</script>
<template>
  <div class="about">
    <h1>This is an about page</h1>
    <CommonMsg msg="I am admin" />
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
