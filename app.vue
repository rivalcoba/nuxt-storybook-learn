<script setup>
// Nuxt realize automatic import
const story = await useStoryblok("home", {
  version: "draft",
});
</script>
<template>
  <StoryblokComponent v-if="story" :blok="story.content"></StoryblokComponent>
</template>
