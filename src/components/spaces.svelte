<script>
	import { onMount } from 'svelte';

	onMount(() => {
		const atlanta = document.querySelector('.atlanta');
		const sanfrancisco = document.querySelector('.sanfrancisco');
		const newyork = document.querySelector('.newyork');
		const sandiego = document.querySelector('.sandiego');
		const portland = document.querySelector('.portland');

		const images1 = document.querySelector('.images1');
		const images2 = document.querySelector('.images2');

		// remove hidden class from images1
		images1.classList.remove('hidden');

		// add hidden class to images2
		images2.classList.add('hidden');

		// add underline class to atlanta
		atlanta.classList.add('underline');

		// remove underline class from sanfrancisco and newyork and sandiego and portland
		sanfrancisco.classList.remove('underline');
		newyork.classList.remove('underline');
		sandiego.classList.remove('underline');
		portland.classList.remove('underline');

		atlanta.addEventListener('click', () => {
			// remove hidden class from images1
			images1.classList.remove('hidden');

			// add hidden class to images2
			images2.classList.add('hidden');

			// add underline class to atlanta
			atlanta.classList.add('underline');

			// remove underline class from sanfrancisco and newyork and sandiego and portland
			sanfrancisco.classList.remove('underline');
			newyork.classList.remove('underline');
			sandiego.classList.remove('underline');
			portland.classList.remove('underline');
		});

		sanfrancisco.addEventListener('click', () => {
			// add hidden class to images1
			images1.classList.add('hidden');

			// remove hidden class from images2
			images2.classList.remove('hidden');

			// add underline class to sanfrancisco
			sanfrancisco.classList.add('underline');

			// remove underline class from atlanta and newyork and sandiego and portland
			atlanta.classList.remove('underline');
			newyork.classList.remove('underline');
			sandiego.classList.remove('underline');
			portland.classList.remove('underline');
		});

		newyork.addEventListener('click', () => {
			// add hidden class to images1
			images1.classList.remove('hidden');

			// remove hidden class from images2
			images2.classList.add('hidden');

			// add underline class to newyork
			newyork.classList.add('underline');
			// remove underline class from atlanta and sanfrancisco and sandiego and portland
			atlanta.classList.remove('underline');
			sanfrancisco.classList.remove('underline');
			sandiego.classList.remove('underline');
			portland.classList.remove('underline');
		});

		sandiego.addEventListener('click', () => {
			// add hidden class to images1
			images1.classList.add('hidden');

			// remove hidden class from images2
			images2.classList.remove('hidden');

			// add underline class to sandiego
			sandiego.classList.add('underline');

			// remove underline class from atlanta and newyork and sandiego and portland
			atlanta.classList.remove('underline');
			sanfrancisco.classList.remove('underline');
			newyork.classList.remove('underline');
			portland.classList.remove('underline');
		});

		portland.addEventListener('click', () => {
			// add hidden class to images1
			images1.classList.remove('hidden');

			// remove hidden class from images2
			images2.classList.add('hidden');

			// add underline class to portland
			portland.classList.add('underline');

			// remove underline class from atlanta and newyork and sandiego and portland
			atlanta.classList.remove('underline');
			sanfrancisco.classList.remove('underline');
			newyork.classList.remove('underline');
			sandiego.classList.remove('underline');
		});
	});
</script>

<template>
	<div class="bg-[#00272e] text-gray-100 px-[8%]">
		<div class="flex items-center pt-32 font-roboto pb-40">
			<p class="text-xl">
				With over 1600 spaces citywide, we offer you<br /> workspace where and how you need it.
			</p>
			<a href="/" class="ml-auto"
				><p
					class="flex gap-2 hover:gap-4 transition-all justify-center items-center text-lg border-b-2 border-gray-300-2"
				>
					Find a space near you <svg
						xmlns="http://www.w3.org/2000/svg"
						class="h-6 w-6"
						fill="none"
						viewBox="0 0 24 24"
						stroke="currentColor"
						stroke-width="1.8"
					>
						<path stroke-linecap="round" stroke-linejoin="round" d="M13 7l5 5m0 0l-5 5m5-5H6" />
					</svg>
				</p></a
			>
		</div>
		<div class="flex pb-24">
			<div class="z-20">
				<div class="flex gap-8 items-top mb-12">
					<p class="font-roboto text-lg">331</p>
					<h2
						class="atlanta font-roboto text-7xl hover:underline underline-offset-8 hover:cursor-pointer"
					>
						Atlanta
					</h2>
				</div>
				<div class="flex gap-8 items-top mb-12">
					<p class="font-roboto text-lg">276</p>
					<h2
						class="sanfrancisco font-roboto text-7xl hover:underline underline-offset-8 hover:cursor-pointer"
					>
						San Francisco
					</h2>
				</div>
				<div class="flex gap-8 items-top mb-12">
					<p class="font-roboto text-lg">348</p>
					<h2
						class="newyork font-roboto text-7xl hover:underline underline-offset-8 hover:cursor-pointer"
					>
						New York
					</h2>
				</div>
				<div class="flex gap-8 items-top mb-12">
					<p class="font-roboto text-lg">387</p>
					<h2
						class="sandiego font-roboto text-7xl hover:underline underline-offset-8 hover:cursor-pointer"
					>
						San Diego
					</h2>
				</div>
				<div class="flex gap-8 items-top pb-20">
					<p class="font-roboto text-lg">358</p>
					<h2
						class="portland font-roboto text-7xl hover:underline underline-offset-8 hover:cursor-pointer"
					>
						Portland
					</h2>
				</div>
			</div>
			<div>
				<div class="flex hidden images1">
					<img
						src="https://images.unsplash.com/photo-1659197151611-fcc49587b284?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=735&q=80"
						alt="architecture"
						class="z-10 ml-[200px] mt-[-100px] w-96 h-[600px]"
					/>
					<img
						src="https://images.unsplash.com/photo-1659286949592-8b2d5ab6fe90?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=80"
						alt="architecture"
						class="z-0 ml-[-100px] mt-[100px] w-96 h-[500px]"
					/>
				</div>
				<div class="flex hidden images2">
					<img
						src="https://images.unsplash.com/photo-1659132394880-d55f55b3a794?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=80"
						alt="architecture"
						class="z-10 ml-[200px] mt-[-100px] w-96 h-[600px]"
					/>
					<img
						src="https://images.unsplash.com/photo-1659132396004-8a98997b2f51?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=80"
						alt="architecture"
						class="z-0 ml-[-60px] mt-[60px] w-96 h-[550px]"
					/>
				</div>
			</div>
		</div>
	</div>
</template>
