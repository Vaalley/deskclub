<script>
	// Import Swiper Svelte components
	import { Swiper, SwiperSlide } from 'swiper/svelte';
	import { Navigation, Pagination, Scrollbar, A11y, Autoplay } from 'swiper';

	// Import Swiper styles
	import 'swiper/css';
</script>

<template>
	<div class="ml-[8%] mb-36">
		<div class="font-roboto">
			<p class="uppercase text-green-500 font-bold text-lg mb-6">What We Offer</p>
			<h2 class="text-6xl font-bold mb-16">From desks to offices and <br /> entire headquarters</h2>
		</div>
		<div>
			<Swiper
				modules={[Navigation, Pagination, Scrollbar, A11y, Autoplay]}
				spaceBetween={40}
				slidesPerView={3}
				on:slideChange={() => console.log('slide change')}
				on:swiper={(e) => console.log(e.detail[0])}
			>
				<SwiperSlide>
					<img src="../../static/images/office-4.webp" alt="Office" class="w-full mb-8" />
					<h4 class="font-roboto font-semibold text-2xl mb-1">On-Demand Spaces</h4>
					<p class="font-roboto font-medium text-lg text-gray-600 mb-4">
						Commitment free workspaces when you need them.
					</p>
					<a href="/"
						><p
							class="flex gap-2 items-center font-roboto font-medium text-lg border-b-2 border-gray-300 w-fit"
						>
							Browse hourly space<svg
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
				</SwiperSlide>
				<SwiperSlide>
					<img src="../../static/images/office-4.webp" alt="Office" class="w-full mb-8" />
					<h4 class="font-roboto font-semibold text-2xl mb-1">On-Demand Spaces</h4>
					<p class="font-roboto font-medium text-lg text-gray-600 mb-4">
						Commitment free workspaces when you need them.
					</p>
					<a href="/"
						><p
							class="flex gap-2 items-center font-roboto font-medium text-lg border-b-2 border-gray-300 w-fit"
						>
							Browse hourly space<svg
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
				</SwiperSlide>
				<SwiperSlide>
					<img src="../../static/images/office-4.webp" alt="Office" class="w-full mb-8" />
					<h4 class="font-roboto font-semibold text-2xl mb-1">On-Demand Spaces</h4>
					<p class="font-roboto font-medium text-lg text-gray-600 mb-4">
						Commitment free workspaces when you need them.
					</p>
					<a href="/"
						><p
							class="flex gap-2 items-center font-roboto font-medium text-lg border-b-2 border-gray-300 w-fit"
						>
							Browse hourly space<svg
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
				</SwiperSlide>
				<SwiperSlide>
					<img src="../../static/images/office-4.webp" alt="Office" class="w-full mb-8" />
					<h4 class="font-roboto font-semibold text-2xl mb-1">On-Demand Spaces</h4>
					<p class="font-roboto font-medium text-lg text-gray-600 mb-4">
						Commitment free workspaces when you need them.
					</p>
					<a href="/"
						><p
							class="flex gap-2 items-center font-roboto font-medium text-lg border-b-2 border-gray-300 w-fit"
						>
							Browse hourly space<svg
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
				</SwiperSlide>
				<SwiperSlide>
					<img src="../../static/images/office-4.webp" alt="Office" class="w-full mb-8" />
					<h4 class="font-roboto font-semibold text-2xl mb-1">On-Demand Spaces</h4>
					<p class="font-roboto font-medium text-lg text-gray-600 mb-4">
						Commitment free workspaces when you need them.
					</p>
					<a href="/"
						><p
							class="flex gap-2 items-center font-roboto font-medium text-lg border-b-2 border-gray-300 w-fit"
						>
							Browse hourly space<svg
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
				</SwiperSlide>
			</Swiper>
		</div>
	</div>
</template>
