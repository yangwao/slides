<template>
  <div m="auto">
    <img  width="300" src="/kodragon.png">
    <h3 border="~ gray-400 opacity-50" w="75" p="2">{{ name }}</h3>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const props = defineProps({
  id: {
    default: '',
  },
})

const name = ref('KoDragon')
</script>


