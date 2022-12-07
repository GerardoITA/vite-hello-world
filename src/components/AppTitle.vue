<script setup>
defineProps({
    msg: {
        type: String,
        required: true
    }
})
</script>
<template>
<h1 class="h1">{{ msg }}</h1>
</template>

<style scoped>
    .h1 {color: red }
</style>