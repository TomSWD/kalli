<template>
  <img class="hero-pic" src="/hero-pic.jpg" />
</template>

<script>
export default {
  name: "HeroImage",
};
</script>

<style>
  .hero-pic {
    position: absolute;
    z-index: 10;
    top: 0;
    left: 100px;
    width: calc(50vw + 50% - 100px);
    margin-right: -120px;
    min-width: 100%;
    min-height: 100%;
    object-fit: cover;
  }
  @media only screen and (max-width: 767px) {
  .hero-pic {
    left :0px;
  }
}
</style>