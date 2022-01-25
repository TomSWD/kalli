<template>
<div class="hero">
  <div class="hero__container container">
    <HeroImage/>
    <HeroTitle/>
  </div>
</div>

</template>

<script>
  import HeroImage from './HeroImage.vue'
  import HeroTitle from './HeroTitle'

  export default {
    name: 'Hero',
    components: {
      HeroImage,
      HeroTitle,
    }
  }
</script>

<style scoped>
  .hero {
    background-color: #222;
    color: white;
    overflow: hidden;
    height: 100vh;
    min-height: 620px;
  }

  .hero__container {
    display: flex;
    align-items: center;
    height: 100%;
    position: relative;
  }
</style>