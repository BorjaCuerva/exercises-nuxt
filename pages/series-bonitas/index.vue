<script setup lang="ts">
const category = "aventuras";
</script>
<template>
  <div>
    <h1>Series bonitas</h1>
    <NuxtLink :to="`/series-bonitas/${category}`">
      Ver Episodios de Aventura
    </NuxtLink>
  </div>
</template>
