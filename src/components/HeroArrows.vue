<template>
  <div class="hero-nav-arrows arrows-white">
    <a class="arrow-left">
      <svg class="arrow icon icon-arrow-left" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 18 9">
        <path
          d="M5 6.9c.4.4.4 1 0 1.4h0c-.4.4-1 .4-1.4 0L.3 5a1 1 0 0 1 0-1.4L3.6.3A1 1 0 0 1 5 .3h0a1 1 0 0 1 0 1.4L3.4 3.3H17a1 1 0 0 1 1 1h0a1 1 0 0 1-1 1H3.4L5 6.9z">
        </path>
      </svg>
    </a>
    <a class="arrow-right">
      <svg class="arrow icon icon-arrow-right" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 18 9">
        <path
          d="M13 6.9c-.4.4-.4.9-.1 1.3l.1.1c.4.4 1 .4 1.4 0L17.7 5a1 1 0 0 0 0-1.4L14.4.3a1 1 0 0 0-1.3-.1l-.1.1a1 1 0 0 0 0 1.4l1.6 1.6H1a1 1 0 0 0-1 .9v.1a1 1 0 0 0 1 1h13.6L13 6.9z">
        </path>
      </svg>
    </a>
  </div>
</template>

<script>
export default {
  name: 'HeroArrows',
};
</script>

<style scoped>
  .arrows-white {
    display: flex;
    margin-left: -13.5px;
 }

  .arrow-left,
  .arrow-right{
    display: flex;
    align-items: center;
    justify-content: center;
    width: 47px;
    height: 40px;
    text-align: center;
  }

  .arrow-left:hover,
  .arrow-right:hover{
    background-color: #aaa;
  }

  .arrow-left:hover path,
  .arrow-right:hover path{
    fill: #000;
  }

  .arrow{
    font-family: Arial;
    height: 10px;
    width: 20px;  
    color: #000000;
  }

  .arrow path{
    fill: #fff;
  } 
</style>