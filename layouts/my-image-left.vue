<template>
  <div class="relative h-full intro grid grid-cols-12">
    <div class="absolute h-full w-full" style="z-index: -10">
      <BubbleFrame v-if="!hideFrame"/>
    </div>
    <div
      v-if="image"
      :class="[equal ? 'col-span-6' : 'col-span-4', 'my-auto h-full']"
    >
      <img
        :src="image"
        class="my-auto mx-auto h-auto"
        :style="{
          maxHeight: '100%',
        }"
      />
    </div>
    <div
      :class="[
        'slidev-layout my-auto',
        image ? 'col-span-6' : 'col-span-12',
        equal ? 'col-span-6' : 'col-span-8',
      ]"
    >
      <slot />
    </div>
  </div>
</template>

<script setup lang="ts">
// Dependencies
import { defineProps } from "vue";

const props = defineProps({
  image: {
    type: String,
    required: true,
  },
  equal: {
    type: Boolean,
    default: false,
    required: false,
  },
  hideFrame: {
    type: Boolean,
    default: false,
  }
});
</script>