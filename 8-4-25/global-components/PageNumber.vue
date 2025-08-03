<template>
  <!-- Page numbers disabled -->
</template>

<script setup>
import { computed } from 'vue'
import { useSlideContext } from '@slidev/client'

const { $slidev } = useSlideContext()
</script>

<style scoped>
.page-number {
  position: fixed;
  bottom: 2rem;
  right: 2rem;
  font-size: 0.875rem;
  color: #666;
  font-weight: 500;
  z-index: 100;
  pointer-events: none;
}
</style>