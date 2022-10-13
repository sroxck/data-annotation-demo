<script setup lang="ts">
import sf from './components/annotation.vue'
const props = defineProps<{
  modelValue?: boolean,
}>()

</script>

<template>
  <div>
    <sf></sf>
    <slot/>
  </div>
</template>
