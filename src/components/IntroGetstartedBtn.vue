<template>
  <a class="get-started-button" href="#">Get started</a>
</template>

<script>
export default {
  name: 'IntroGetstartedBtn',
}
</script>

<style scoped>
	.get-started-button {
		text-decoration: none;
		text-transform: uppercase;
		color: #fff;
		font-size: 12px;
		font-weight: 500;
		letter-spacing: 1px;
		line-height: 14.4px;
		border: 2px solid #222;
		padding: 14px 18px;
		background-color: #222;
	}

	.get-started-button:hover {
		transition: .2s;
		background-color: #aaa;
		color: #222;
		border: 2px solid #aaa;
	}
</style>