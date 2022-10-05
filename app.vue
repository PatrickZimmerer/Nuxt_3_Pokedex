<template>
	<div>
		<nuxt-page></nuxt-page>
	</div>
</template>

<script setup>
import '@/assets/css/tailwind.css';
</script>

<style>
body {
	background-color: black;
	height: 100%;
}
/*  BOSCH CUSTOM SCROLLBAR   */
::-webkit-scrollbar {
	width: 0.25rem;
	height: 0;
}

::-webkit-scrollbar-track {
	background-color: rgba(0, 0, 0, 0.4);
	border-radius: 0.625rem;
}

::-webkit-scrollbar-thumb {
	background-color: #dfdfdf;
	border-radius: 0.625rem;
}
</style>
