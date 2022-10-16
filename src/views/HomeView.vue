<script setup>
import Info from '../components/Info.vue';
import { useStore } from '../composables/useStore'
import { onMounted, h } from "vue"
const store = useStore()


onMounted(() => {
  store.shadowText = h('h1', `h1 a traves de h-function`);
})

</script>

<template>
  <main>
    <h1>Im a HomeView title</h1>
    <Info></Info>
  </main>
</template>