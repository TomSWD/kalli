<template>
  <div class="section-main-container">
    <div class="section-container container">
      <div class="section-left-container">
        <SectionPaginationTitle/>
        <SectionPagination/>
        <SectionArrows/>
      </div>
      <div class="section-pic-container">
        <SectionImage/>
      </div>
      <div class="section-right-container">
        <div class="section-text-up">
          <SectionTxtUpTitle/>
          <SectionTxtUp/>
        </div>
        <div class="section-text-down">
          <SectionTxtDwnTitle/>
          <SectionTxtDwn/>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  import SectionPaginationTitle from './SectionPaginationTitle.vue'
  import SectionPagination from './SectionPagination.vue'
  import SectionArrows from './SectionArrows.vue'
  import SectionImage from './SectionImage.vue'
  import SectionTxtUpTitle from './SectionTxtUpTitle.vue'
  import SectionTxtUp from './SectionTxtUp.vue'
  import SectionTxtDwnTitle from './SectionTxtDwnTitle.vue'
  import SectionTxtDwn from './SectionTxtDwn'

  export default {
    name: 'Section',
    components: {
      SectionPaginationTitle,
      SectionPagination,
      SectionArrows,
      SectionImage,
      SectionTxtUpTitle,
      SectionTxtUp,
      SectionTxtDwnTitle,
      SectionTxtDwn,
    }
  }
</script>

<style scoped>
  .section-main-container{
    width: 1349px;
    padding-top: 80px;
    padding-bottom: 80px;
    max-width: 100%;
    
  }
  .section-container {
    display: flex;
    width:920px;
    height:480px;
    /* max-width: 100%; */
  }

  .section-left-container {
    width:256px;
    height:252px;
    margin-top: 114px;
    margin-right: 40px;
  }

  @media only screen and (max-width: 1240px) {
  .section-left-container {
    margin-right: 0px;
  }
}

  @media only screen and (max-width: 1024px) {
  .section-left-container {
    width: 180px;
    margin-top: 45px;
    margin-right: 40px;
  }
}

  .section-right-container {
    width: 264px;
    height: 332px;
    margin-left:50px;
    margin-top: 74px;
    margin-right: -50px;
  }

  @media only screen and (max-width: 1020px) {
  .section-right-container {
    margin-left: 40px;
    width: 328px;
    height: 228px;
  }
}
  .section-text-up {
    margin-bottom: 80px;
  }
   @media only screen and (max-width: 1020px) {
  .section-text-up {
    margin-bottom: 40px;
  }
}
</style>