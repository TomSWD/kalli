<template>
  <div class="hero-nav-pagination pagination">
    <div class="page-number">01</div>
    <div class="slider">
      <a class="slide slide01 active" href="/"></a>
      <a class="slide slide02" href="/"></a>
      <a class="slide slide03" href="/"></a>
    </div>
    <div class="page-number">03</div>
  </div>
</template>

<script>
export default {
  name: 'HeroPagination',
}
</script>

<style scoped>
  .pagination {
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 20px;
    width: 160px;
  }

  .slide {
    display: block;
    width: 41.08px;
    height: 14px;
    border-color: #222;
    border-style: solid;
    border-width: 6px 5px 6px 5px;
    border-radius: 2px;
    background-color: white;
    opacity: .2;
    transition: opacity;
    }

    .slide:not(.active):hover {
      opacity: .6;
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

  .page-number {
    font-size: 12px;
    color: #fff;
    }
</style>