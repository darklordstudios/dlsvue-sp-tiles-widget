<script setup lang="ts">
import { ref, onMounted } from 'vue'
import { ImagePicker } from 'dls-vue'

const tileswidget = ref(null)

onMounted(() => {
  console.log('MOUNTED')
})
</script>

<template>
  <div ref="tileswidget"><ImagePicker />></div>
</template>

<style scoped></style>
