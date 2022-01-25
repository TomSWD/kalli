<template>
  <div class="intro-main-container">
    <div class="intro__container container">
      <div class="intro__pic">
        <IntroImage />
      </div>
      <div class="intro__right-container">
        <div class="intro__heading">
          <IntroTitle />
        </div>
        <IntroText />
        <div class="intro__button-section">
          <IntroLoginBtn />
          <IntroGetstartedBtn />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import IntroImage from "./IntroImage.vue";
import IntroTitle from "./IntroTitle.vue";
import IntroText from "./IntroText.vue";
import IntroLoginBtn from "./IntroLoginBtn.vue";
import IntroGetstartedBtn from "./IntroGetstartedBtn.vue";

export default {
  name: "Intro",
  components: {
    IntroImage,
    IntroTitle,
    IntroText,
    IntroLoginBtn,
    IntroGetstartedBtn,
  },
};
</script>

<style scoped>
  .intro-main-container {
    width: 1349px;
    padding-top: 80px;
    padding-bottom: 80px;
  }

  .intro__container {
    display: flex;
    width: 920px;
    height: 480px;
    align-items: center;
  }

  .intro__right-container {
    margin-left: auto;
    width: 445px;
    height: 386px;
  }
  
  .intro__heading {
    color: #222;
    font-size: 36px;
    font-weight: 600;
    margin-bottom: 60px;
  }

  .intro__button-section {
    display: flex;
  }
</style>