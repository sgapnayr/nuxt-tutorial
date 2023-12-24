<template>
  <div class="button">{{ buttonText }}</div>
</template>

<script setup lang="ts">
defineProps<{
  buttonText?: string;
}>();
</script>

<style scoped>
.button {
  background-color: red;
  padding: 1rem 2rem;
  color: white;
  border-radius: 16px;
  box-shadow: 1px 1px 2px rgba(0, 0, 0, 0.1);
}
</style>
