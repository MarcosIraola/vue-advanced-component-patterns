<script setup>
import {useStore} from '../composables/useStore';

const store = useStore();

store.shadowText = `Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
            Numquam quibusdam officia mollitia reiciendis provident quos a 
            tempora eos aliquid, ullam at natus nostrum sit, harum qui. 
            Quisquam harum optio voluptatem?`
</script>

<template>
    <div class="text">
        {{ store.shadowText }}
    </div>
</template>

<style scoped>
    .text {
        background-color: rgb(202, 42, 42);
        padding: 20px;
    }

</style>