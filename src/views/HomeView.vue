<script setup>
import Info from '../components/Info.vue';
import {useStore} from '../composables/useStore'
import {onMounted} from "vue"
const store = useStore()


onMounted(() => {
  store.shadowText = "123";
})

</script>

<template>
  <main>
    <h1>Im a HomeView title</h1>
    <Info>
      <template v-slot:shadow-box-slot>
      </template>
    </Info>
  </main>
</template>
