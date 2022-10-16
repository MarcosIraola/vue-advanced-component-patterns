<script setup>
import ShadowBox from '../primitives/Shadow-box.vue';
</script>

<template>
    <h1>Info Component</h1>
    <ShadowBox>
        <template v-slot>
            <slot name="shadow-box-slot"></slot>
        </template>
    </ShadowBox>
</template>

<style scoped>

</style>