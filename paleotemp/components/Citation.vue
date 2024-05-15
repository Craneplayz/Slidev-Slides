<script setup lang="ts">
import { ref } from 'vue'

const props = defineProps({
  src: {
    default: "",
  },
})

const src = ref(props.src)
</script>

<template>
    <footer class="absolute bottom-0 left-0 p-2">
        <carbon:document-attachment class="inline text-stone-600"/>	
        <span class="pl-1 text-sm text-stone-600"> {{ src }} </span>
    </footer>
</template>