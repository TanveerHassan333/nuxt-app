<template>
    Page id is: {{ $route.params.id }}
</template>
<script setup>
const nuxt = useNuxtApp();

console.log(nuxt);
</script>