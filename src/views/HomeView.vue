<script setup>
import Info from '../components/Info.vue';
import { useStore } from '../composables/useStore'
import { onMounted, h } from "vue"
const store = useStore()

// no me esta tomando el jsx

onMounted(() => {
  store.shadowText = h('h1', `h1 from h-function`);
});

</script>

<template>
  <main>
    <Info></Info>
  </main>
</template>