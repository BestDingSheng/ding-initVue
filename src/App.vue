<template>
  <div id="app">
  	<div class="box">
  		<img src="./assets/logo.png" alt="">
  		<h1>hello ding-cli </h1>
  	</div>
  </div>
</template>

<script>

</script>

<style scoped lang="scss">
	$baseColor: #00f;
	.box{
		text-align: center;
		margin: 100px 0;
	}
	#app {
		.container {
			width: 200px;
			height: 200px;
			border: 1px solid $baseColor;
			box-shadow: 0 0 8px #000;
			transition: all .2s;
			border-radius: 10px;
			display: flex;
		}
	}
</style>
