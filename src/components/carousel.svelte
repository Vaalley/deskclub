<script>
	// Import Swiper Svelte components
	import { Swiper, SwiperSlide } from 'swiper/svelte';

	// Import Swiper styles
	import 'swiper/css';
</script>

<Swiper
	spaceBetween={50}
	slidesPerView={1}
	navigation
	pagination
	loop
	on:slideChange={() => console.log('slide change')}
	on:swiper={(e) => console.log(e.detail[0])}
>
	<SwiperSlide
		><img
			src="../../static/images/office-1.webp"
			alt="Office"
			class="w-full my-[-15vh]"
		/></SwiperSlide
	>
	<SwiperSlide
		><img
			src="../../static/images/office-2.webp"
			alt="Office"
			class="w-full my-[-15vh]"
		/></SwiperSlide
	>
	<SwiperSlide
		><img
			src="../../static/images/office-3.webp"
			alt="Office"
			class="w-full my-[-15vh]"
		/></SwiperSlide
	>
	...
</Swiper>
