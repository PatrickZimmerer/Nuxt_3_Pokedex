<template>
	<div>
		<div class="bg-container">
			<slot></slot>
		</div>
	</div>
</template>

<script></script>

<style scoped>
.bg-container {
	padding: 8px 0px;
	background-image: url('../assets/img/pokemon-bg.jpeg');
	background-position: 50% 30%;
	background-repeat: repeat;
	background-attachment: fixed;
}
</style>
