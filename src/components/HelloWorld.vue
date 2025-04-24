<template>
  <div>
    <h1>{{ message }}</h1>
    <input v-model="message" />
  </div>
</template>

<script setup>
import { ref } from 'vue'

const message = ref('hello')
</script>
