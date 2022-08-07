<script setup>
// Nuxt realize automatic import
const story = await useStoryblok("home", {
  version: "draft",
});
</script>
<template>
  <pre>{{ story }}</pre>
</template>
