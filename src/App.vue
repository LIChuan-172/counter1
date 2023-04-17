<script setup lang="ts">
// @ts-ignore
import { provide } from "vue"
import Counter from "./lib/Counter.vue"

provide("message", "Hello from lib");
</script>

<template>
  <div id="app">
    <Counter />
  </div>
</template>
