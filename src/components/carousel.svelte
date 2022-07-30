<script>
	// Import Swiper Svelte components
	import { Swiper, SwiperSlide } from 'swiper/svelte';
	import { Navigation, Pagination, Scrollbar, A11y, Autoplay } from 'swiper';

	// Import Swiper styles
	import 'swiper/css';
</script>

<Swiper
	modules={[Navigation, Pagination, Scrollbar, A11y, Autoplay]}
	autoplay={{
		delay: 3000,
		disableOnInteraction: false
	}}
	loop={true}
	class="mb-44"
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
</Swiper>
