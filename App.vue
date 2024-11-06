<script setup lang="ts">
import { ref } from "vue";
const count = ref(69);
</script>

<template>
  <h1>Hello from vue</h1>
  <p>Count is: {{ count }}</p>
</template>
