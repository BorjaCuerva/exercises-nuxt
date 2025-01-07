<script setup lang="ts">
definePageMeta({
  layout: false,
});
</script>
<template>
  <section>
    <NuxtLayout name="catalogue-layout">
      <div>
        <h1>Catálogo</h1>
      </div>
      <NuxtLink class="button" :to="{ name: 'index' }"> HOME </NuxtLink>
    </NuxtLayout>
  </section>
</template>

<style scoped>
section {
  display: flex;
  flex-direction: column;
  gap: 1em;
}
.button {
  padding: 1em 2em;
  background-color: #fff;
  color: #000;
  width: fit-content;
}
</style>
