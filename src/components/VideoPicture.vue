<template>
  <div class="video-image" style="background-image: url(/video-pic.jpg);">
    <slot/>
  </div>
</template>

<script>
  export default {
    name: 'VideoPicture',
  }
</script>

<style scoped>
  .video-image {
    height: 600px;
    padding: 40px;
  }
</style>
