<script setup lang='ts'>
const props = defineProps<{
  type: 'emoji-only' | 'text-only' | 'emoji-and-text'
}>()

const emits = defineEmits<{
  
}>()
</script>

<template>
  <div>
    <button type="button" :class="classes" @click="onClick"><slot></slot></button>
  </div>    
</template>