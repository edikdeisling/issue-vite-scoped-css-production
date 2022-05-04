<script setup lang="ts">
  import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <HelloWorld class="parent-class" />
</template>

<style scoped>
  .parent-class {
    background-color: red;
  }
</style>
