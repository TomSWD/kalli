<template>
  <div class="hero-title">Make it simple, but significant</div>
</template>

<script>
export default {
  name: "HeroTitle",
};
</script>

<style scoped>
.hero-title {
  position: absolute;
  z-index: 20;
  width: 580px;
  height: 148px;
  font-size: 64px;
  line-height: 74px;
  font-weight: 600;
  margin-top: 18px;
  margin-left: 5px;
}
@media only screen and (max-width: 1023px) {
  .hero-title {
    margin-bottom: 58px;
    margin-left: 40px;
  }
}
@media only screen and (max-width: 767px) {
  .hero-title {
    font-size: 36px;
    line-height: 1.27778;
    margin-top: 0px;
  }
}
@media only screen and (max-width: 635px) {
  .hero-title {
    width: 473px;
    margin-left: 40px;
  }
}
</style>