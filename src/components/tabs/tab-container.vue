<style lang="scss" rel="scss" scoped>
    .vue-tab-container {
        height: 100%;
        width: 100%;
        position: relative;
        display: flex;
        flex-direction: column;
    }
</style>

<template>
    <div class="vue-tab-container">
        <slot></slot>
    </div>
</template>

<script lang="babel">

    export default {
        name: 'v-tab-container'
    }
</script>