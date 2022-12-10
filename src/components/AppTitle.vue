<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>La mia prima app con vite</h1>

</template>

<style scoped>
h1 {
  color: red;
  font-size: 50px;
}
</style>
