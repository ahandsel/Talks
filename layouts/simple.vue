<!--
  Usage:

```md
---
layout: basic
---

# Title

Text

-->

<script setup lang="ts">
const props = defineProps({
  class: {
    type: String,
  },
});
</script>

<template>
  <div class="slidev-layout absolute h-full w-full intro">
    <div class="absolute h-full w-full" style="z-index: -10">
    <!-- https://github.com/lightvue/slidev-theme-light-icons/blob/master/components/BubbleFrame.vue -->
      <BubbleFrame />
    </div>
    <div>
        <slot />
    </div>
  </div>
</template>