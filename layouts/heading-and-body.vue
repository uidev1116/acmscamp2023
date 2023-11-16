<template>
  <div class="relative h-full intro grid grid-cols-12">
    <div class="absolute h-full w-full" style="z-index: -10">
      <BubbleFrame v-if="!hideFrame"/>
    </div>
    <div class="slidev-layout col-span-12">
      <div class="font-bold">
        <slot name="heading" />
      </div>
      <div>
        <slot name="body" />
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
// Dependencies
import { defineProps } from "vue";

defineProps({
  hideFrame: {
    type: Boolean,
    default: false,
  }
});
</script>