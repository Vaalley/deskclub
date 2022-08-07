<script>
	import Navbar from '../components/navbar.svelte';
	import Hero from '../components/hero.svelte';
	import Carousel from '../components/carousel.svelte';
	import Features from '../components/features.svelte';
	import Offer from '../components/offer.svelte';
	import Spaces from '../components/spaces.svelte';
</script>

<svelte:head>
	<title>Deskclub</title>
</svelte:head>

<template>
	<Navbar />
	<Hero />
	<Carousel />
	<Offer />
	<Features />
	<Spaces />
</template>
