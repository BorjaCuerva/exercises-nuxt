<script setup lang="ts">
// Accede a los parámetros de la URL
const route = useRoute();
const category = route.params.category;
const title = route.params.title;
</script>

<template>
  <div>
    <h1>Categoría: {{ route.params }}</h1>
    <h1>Categoría: {{ category }}</h1>
    <h2>Título: {{ title }}</h2>
  </div>
</template>
