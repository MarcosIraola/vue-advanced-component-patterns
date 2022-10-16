<script setup>
import Info from '../components/Info.vue';
</script>

<template>
  <main>
    <h1>Im a HomeView title</h1>
    <Info>
      <template v-slot:shadow-box-slot>
        Hello world
      </template>
    </Info>
  </main>
</template>
