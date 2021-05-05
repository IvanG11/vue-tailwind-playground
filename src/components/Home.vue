<template>
  <div class="home flex items-center justify-center h-screen">
    <div class="text-gray-600 font-bold p-10">
      <h2 class="text-6xl text-center">Vue TailwindCSS Playground</h2>
    </div>
  </div>
</template>

<script setup>
import { defineProps, reactive } from 'vue'

defineProps({
  msg: String
})

const state = reactive({ count: 0 })
</script>
