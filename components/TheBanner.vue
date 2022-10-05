<template>
  <div
    class="banner flex h-40 justify-center items-center text-2xl bold font-semibold font-serif"
  >
    {{ text }}
  </div>
</template>

<script setup lang="ts">
const props = defineProps({
  text: String,
});
</script>

<style>
.banner {
  background-color: var(--main-bg-color);
}
</style>
