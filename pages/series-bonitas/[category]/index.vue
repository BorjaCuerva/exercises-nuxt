<script setup lang="ts">
import { useRoute } from "vue-router";

const route = useRoute();
const category = route.params.category;
</script>

<template>
  <div>
    <h1>Series de la categoría: {{ category }}</h1>
    <NuxtLink :to="`/series-bonitas/${category}/spiderman-episodio-1`">
      Ver Spiderman episodio 1
    </NuxtLink>
  </div>
</template>
