<script>
import {defineComponent} from "vue"

// No me esta tomando el jsx
export default defineComponent({
    props: ['info'],
    setup(props) {
        return () => props.info
    }
})
</script>

<template>

</template>