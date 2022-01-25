<template>
  <div class="video-section container">
    <VideoPicture>
      <div class="video-container">
        <VideoFeatured/>
        <VideoTitle/>
        <VideoPlayBtn/>
      </div>
    </VideoPicture>
  </div>
</template>

<script>
  import VideoPicture from './VideoPicture.vue'
  import VideoFeatured from './VideoFeatured.vue'
  import VideoTitle from './VideoTitle.vue'
  import VideoPlayBtn from './VideoPlayBtn.vue'

  export default {
    name: 'VideoSection',
    components: {
      VideoPicture,
      VideoFeatured,
      VideoTitle,
      VideoPlayBtn,
    }
  }
</script>

<style scoped>
  .video-container{
    width: 264px;
    height: 360px;
    padding: 40px 30px;
    background-color: white;
}
</style>