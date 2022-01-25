<template>
  <div class="hero-main-container">
    <div class="hero-nav-container container">
      <HeroArrows/>
      <div class="hero-nav-readmore"><a class="readmore" href="/">Read More</a></div>
      <HeroPagination/>
      <div class="hero-nav-links">
        <a class="hero-link01" href="/">Newsletter</a>
        <a class="hero-link02" href="/">Sign up</a>
      </div>
      <div class="hero-nav-next">
        <a class="hero-next" href="/">
          <div class="hero-next-label">UP NEXT</div>
          <div class="hero-next-title">Design Thinking</div>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
  import HeroArrows from './HeroArrows.vue'
  import HeroPagination from './HeroPagination'

  export default {
    name: 'HeroNav',
    components: {
      HeroArrows,
      HeroPagination,
    }
  }
</script>

<style>
  .hero-main-container {
    background-color: #222;
  }
  .hero-nav-container {
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 1110px;
    height: 100px;
    background-color: #222;
  }
  .readmore {
  text-decoration: none;
  color: #fff;
  width: 83.22px;
  height: 20px;
  }

  .readmore:hover {
    opacity: .6;
    transition: opacity .2s;
  }

  .hero-link01, .hero-link02 {
    text-decoration: none;
    color: #fff;
    font-size: 12px;
    margin: 0 0 0 12px;
    opacity: .6;
    transition: opacity .2s;
  }
  .hero-link01:hover, .hero-link02:hover {
    opacity: 1;
  }

  .hero-next, .hero-nav-next {
    background-color: white;
    text-decoration: none;
    width: 370px;
    height: 170px;
    transition: background .2s;
    align-self: flex-end;
    z-index: 10;
    margin-right: -85px;
  }
  .hero-nav-next:hover{
    background: #eeeeee; 
  }
  .hero-next-label{
    font-family: 'Roboto', sans-serif;
    font-size: 12px;
    letter-spacing: 1px;
    width: 290px;
    height: 15px;
    opacity: 0.6;
    color: #222;
    margin-bottom: 30px;
    margin-top: 55px;
    margin-left: 40px;
  }
  .hero-next-title{
    width: 290px;
    height: 36px;
    color: #222;
    font-size: 24px;;
    font-weight: 500;
    line-height: 36px;
    margin-left: 40px;
  }
</style>