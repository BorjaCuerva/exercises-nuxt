<template>
  <section>
    <div>
      <h1>HOME</h1>
    </div>
    <NuxtLink class="button" :to="{ name: 'catalogo' }"> CATÁLOGO </NuxtLink>
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
