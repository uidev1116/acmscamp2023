<script setup lang="ts">
defineProps({
  video: {
    default: '',
  },
})

</script>

<template>
  <div class="">
    <video :src="video" class="h-full w-full m-auto" loop controls autoplay muted ></video>
  </div>
</template>