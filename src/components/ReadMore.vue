<template>
  <div class="read-more-main-container">
    <div class="read-more-container container">
      <a href="#" class="background-image" style="background-image: url(/about.jpg)">
        <div class="pic-title">About</div>
        <div class="pic-read-more">
          <div class="read-more-txt">Read More</div>
          <svg class="icon icon-arrow-right" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 18 9">
              <path d="M13 6.9c-.4.4-.4.9-.1 1.3l.1.1c.4.4 1 .4 1.4 0L17.7 5a1 1 0 0 0 0-1.4L14.4.3a1 1 0 0 0-1.3-.1l-.1.1a1 1 0 0 0 0 1.4l1.6 1.6H1a1 1 0 0 0-1 .9v.1a1 1 0 0 0 1 1h13.6L13 6.9z"></path>
          </svg>
        </div>
      </a>
      <a href="#" class="background-image" style="background-image: url(/work.jpg)">
        <div class="pic-title">Work</div>
        <div class="pic-read-more">
          <div class="read-more-txt">Read More</div>
          <svg class="icon icon-arrow-right" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 18 9">
            <path d="M13 6.9c-.4.4-.4.9-.1 1.3l.1.1c.4.4 1 .4 1.4 0L17.7 5a1 1 0 0 0 0-1.4L14.4.3a1 1 0 0 0-1.3-.1l-.1.1a1 1 0 0 0 0 1.4l1.6 1.6H1a1 1 0 0 0-1 .9v.1a1 1 0 0 0 1 1h13.6L13 6.9z"></path>
          </svg>
        </div>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ReadMore',
}
</script>

<style scoped>
  .read-more-main-container {
    width: 1349px;
    height: 520px;
    background-color: #222;
  }
  
  .read-more-container {
    display: flex;
    width: 950px;
    height: 360px;
    padding-top: 80px;
  }

  .background-image {
    display:flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    text-decoration: none;
    width: 445px;
    height: 360px; 
    margin-left: 15px;
    margin-right: 15px;
    padding: 64px 30px 30px 30px;
    transition: opacity .2s;
  } 

  .background-image:hover {
    opacity: .8;
  }

  .pic-title {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 385px;
    height: 232px;
    font-family: 'Work Sans',sans-serif;
    color:#fff;
    font-size: 64px;
    line-height: 1.15625;
    font-weight: 600;
  }

  .pic-read-more {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 385px;      
    height: 34px;
    padding-top: 12px;
    border-top: rgba(255,255,255,.2) solid 2px;
  }

  .read-more-txt{
    color: #fff;
    font-size: 16px;
  }

  .icon {
    color: #fff;
    width: 16px;
    height: 8px;
    margin-left: 15px;
  }
</style>