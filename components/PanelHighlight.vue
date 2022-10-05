<template>
<div class="highlight-panel">
    <slot />
</div>
</template>

<script setup lang="ts">
</script>

<style scoped>
.highlight-panel {
    padding: 1.5rem 1rem;
    font-weight: 500;
    background-color: var(--main-bg-color);
    font-style: italic;
}
</style>