<template>
  <div>
    <TheHeader />
    <NuxtPage />
  </div>
</template>

<script setup lang="ts">
useHead({
  link: [
    {
      rel: "prefetch stylesheet",
      href: "/main.css",
    },
  ],
});
</script>
