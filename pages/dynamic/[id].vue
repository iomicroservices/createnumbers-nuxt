<script setup lang="ts">

// javascript to get name of route and log it in console
const route = useRoute();
console.log(route.params.id);

// nuxt built-in composable to access runtime context of Nuxt
const nuxt = useNuxtApp();
console.log(nuxt);

</script>

<template>
    <div> event id: {{  $route.params.id }}</div>
</template>