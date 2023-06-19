<template>
  <h1>Hello World</h1>
  <NuxtLink to="?id=1">Link to id 1</NuxtLink>
  <NuxtLink to="?id=2">Link to id 2</NuxtLink>
  <NuxtLink to="?id=3">Link to id 3</NuxtLink>
</template>
<script setup>
const route = useRoute();
console.log(route.fullPath);
console.log(route.query.id);
</script>
