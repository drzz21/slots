<template>
    <form action="" class="form">
        <slot name="titulo"></slot>
        <slot name="elementos"></slot>
        <slot name="boton"></slot>
    </form>
</template>

<script>
    export default {
        data() {
            return {
            }
        }
    }
</script>

<style scoped>
    h3 {
        color: red;
    }
</style>

