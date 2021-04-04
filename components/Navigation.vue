<template>
	<nav class="navigation">
		<NuxtLink to="/">Home</NuxtLink>
		<NuxtLink to="/about-us">About us</NuxtLink>
		<NuxtLink to="/contact-us">Contact us</NuxtLink>

		<nuxt-link to="/about-us" no-prefetch>About page not prefetched</nuxt-link>
	</nav>
</template>

<style>
	.navigation {
		margin: 15px 0;
		padding: 15px 10px;
	}

	.navigation a {
		display: inline-block;
		margin: 0 10px;
	}
</style>