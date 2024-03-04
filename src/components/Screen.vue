<script setup>
    import { RouterView } from 'vue-router'
</script>

<template>
    <div class="screen">
        <RouterView />
    </div>
</template>

<style scoped>
.screen {
    padding: 16px 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}
</style>
