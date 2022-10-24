<script setup lang="ts">
const props = defineProps({
    title: {
        type: String,
        required: true,
    }
})
</script>

<template>
    I am a {{ title }}
</template>