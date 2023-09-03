<script setup lang="ts">
defineProps<{
  name: string
  desc: string
}>()
</script>

<template>
  <div class="name">
    <h1 class="green">{{ name }}</h1>
    <h3>{{ desc }}</h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.name h1,
.name h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .name h1,
  .name h3 {
    text-align: left;
  }
}
</style>
