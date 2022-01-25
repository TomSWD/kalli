<template>
  <div class="section-pagination pagination">
      <div class="section--page-number">01</div>
      <div class="slider">
         <a class="slide slide01 active" href="/"></a>
         <a class="slide slide02" href="/"></a>
         <a class="slide slide03" href="/"></a>
         <a class="slide slide04" href="/"></a>
      </div>
    </div>
</template>

<script>
export default {
  name: 'SectionPagination',
}
</script>

<style scoped>
  .section-pagination {
  margin-bottom: 40px;
  }

  .pagination {
    color: black;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 20px;
    width: 160px;
  }

  .slide {
    display: block;
    width: 34.41px;
    height: 14px;
    border-color: #fff;
    border-style: solid;
    border-width: 6px 5px 6px 5px;
    border-radius: 2px;
    background-color: #222;
    transition: opacity 0.2s;
    opacity: .3;
    }

  .slide:hover {
    opacity: .7;
  }

  .active {
    opacity: 1;
  }

  .slider {
    display: flex;
    align-items: center;
    margin-left: 5px;
    margin-right: 5px;
  }

  .section--page-number {
    font-size: 12px;
    color: #222;
  }  
</style>
