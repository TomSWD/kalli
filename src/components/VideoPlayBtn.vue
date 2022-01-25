<template>
	<a class="play-section" href="#">
      <div class="play-button">
        <svg class="icon icon-play" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 18">
          <path d="M1 18c-.17 0-.35-.04-.5-.13A1 1 0 0 1 0 17V1A1 1 0 0 1 .5.13a1 1 0 0 1 1 0l13.86 8a1 1 0 0 1 0 1.73l-13.86 8c-.15.1-.33.13-.5.13h0z"></path>
        </svg>
      </div>
      <div class="play-title">Play Video</div>
    </a>
</template>

<script>
export default {
	name: 'VideoPlayBtn',
};
</script>

<style scoped>
	.play-button {
		width: 30px;
		height: 30px;
		background: #e8e8e8;
		border-radius: 50%;
		display: flex;
		justify-content: center;
		align-items: center;
	}

	.icon-play {
		color: #222;
		font-size: 8px;
		width: .89em;
		height: 1em;
		transition: background .2s;
	}
  .play-section {
  display: flex;
  width: 100%;
  height:30px;
  align-items: center;
  margin-top: 123px;
  text-decoration: none;
  }
  
	.play-section:hover .play-button {
		background-color: #aaa;
	}

	.play-title {
	font-size: 16px;
	font-weight: 500;
	margin-left: 10px;
	color: #222;
	}
</style>