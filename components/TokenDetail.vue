<template>
  <div m="auto">
    <img  width="300" src="/kodragon.png">
    <h3 border="~ gray-400 opacity-50" w="75" p="2">{{ name }}</h3>
    <div class="text-ellipsis overflow-hidden"  border="~ gray-400 opacity-50" w="75" p="2">creator: {{ issuer }}</div>
  </div>
</template>

<script setup async lang="ts">
import { ref } from 'vue'
import { ask } from '@kodadot1/uniquery'

const props = defineProps({
  id: {
    default: '1825819407-1',
  },
})

const name = ref('KoDragons#1')

const res: any = await ask<any>(`/bsx/nft/${props.id}`)

console.log(res.data.nft)

const issuer = ref(res.data.nft.issuer)
</script>


