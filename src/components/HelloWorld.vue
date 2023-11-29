<script setup>
import { ref } from "vue";

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <h4>{{ msg }}</h4>

  <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
  </div>

  <div class="card">
    <h2>Practice 3 - Vite, web applications and GitHub Pages</h2>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
