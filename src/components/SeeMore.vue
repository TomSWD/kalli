<template>
  <div class="see-more_container">
    <div class="see-more-title">Simplicity Is The Ultimate<br>Sophistication Trend</div>
    <div class="see-more-dwn-container">
      <div class="see-more-text">Thing yielding. Thing from be lights deep over. May you're our let don't fourth. Likeness beast moved yielding after a is winged divided be. Said image moveth.</div>
      <div class="see-more-button">
        <a href="#" class="see-button">
          <div class="see-btn">
            <svg class="icon icon-grid" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 17 17">
              <path d="M1.5 14c.8 0 1.5.7 1.5 1.5S2.3 17 1.5 17 0 16.3 0 15.5.7 14 1.5 14zm14 0c.8 0 1.5.7 1.5 1.5s-.7 1.5-1.5 1.5-1.5-.7-1.5-1.5.7-1.5 1.5-1.5zm-7 0c.8 0 1.5.7 1.5 1.5S9.3 17 8.5 17 7 16.3 7 15.5 7.7 14 8.5 14zm-7-7C2.3 7 3 7.7 3 8.5S2.3 10 1.5 10 0 9.3 0 8.5.7 7 1.5 7zm14 0c.8 0 1.5.7 1.5 1.5s-.7 1.5-1.5 1.5S14 9.3 14 8.5 14.7 7 15.5 7zm-7 0c.8 0 1.5.7 1.5 1.5S9.3 10 8.5 10 7 9.3 7 8.5 7.7 7 8.5 7zm-7-7C2.3 0 3 .7 3 1.5S2.3 3 1.5 3 0 2.3 0 1.5.7 0 1.5 0zm14 0c.8 0 1.5.7 1.5 1.5S16.3 3 15.5 3 14 2.3 14 1.5 14.7 0 15.5 0zm-7 0c.8 0 1.5.7 1.5 1.5S9.3 3 8.5 3 7 2.3 7 1.5 7.7 0 8.5 0z"></path>
            </svg><span class="btn-txt">See more</span>
          </div>  
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SeeMore',
}
</script>

<style>
  .see-more_container {
    width: 920px;
    height: 328px;
    padding-top: 80px;
    margin: auto;
  }

  .see-more-title {
    font-size: 36px;
    font-weight: 600;
    line-height: 1.27778;
    color: #222;
    margin-bottom: 60px;
  }

  .see-more-dwn-container {
    display:flex;
    width: 920px;
    height: 96px;
    width: 100%;
  }

  .see-more-text {
    font-family: 'Roboto',sans-serif;
    font-size: 18px;
    font-weight: 400;
    color: #222;
    opacity: .6;
    line-height: 1.77778;
    width: 712px;
    column-count: 2;
    column-gap: 70px;
  }

  .see-more-button {
    margin-top: 10px;
    margin-left: 70px;
  }

  .see-btn {
    display: inline-block;
    text-decoration: none; 
    color: #fff;
    letter-spacing: 1px;
    padding: 14px 18px;
    border: 2px solid #222;
    background-color: #222;
    transition: all .2s;
  }

  .icon-grid {
    width: 14px;
    height: 14px;
    margin: -2px 0;
  }

  .btn-txt {
    text-transform: uppercase;
    font-size: 12px;
    margin: 0px 0px 0px 14px;
    vertical-align: middle;
  }

  .see-btn:hover {
    background-color: #aaa;
    border-color: #aaa;
    color: #222;
  }
</style>