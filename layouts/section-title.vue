<template>
  <div class="slidev-layout relative h-full w-full intro grid grid-cols-12">
    <div class="absolute h-full w-full" style="z-index: -10">
      <BubbleFrame v-if="!hideFrame"/>
    </div>
    <div class="col-span-12 m-auto">
      <div class="grid place-content-center">
        <slot />
      </div>
    </div>
  </div>
</template>
<script setup lang="ts">
import { defineProps } from "vue";
defineProps({
  hideFrame: {
    type: Boolean,
    default: false,
  }
});
</script>