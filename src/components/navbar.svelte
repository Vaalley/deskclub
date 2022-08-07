<template>
	<div class="h-24 w-full flex items-center justify-end font-roboto font-medium">
		<div class="mr-auto ml-[3%] text-2xl font-black">
			<p>deskclub</p>
		</div>
		<div class="mr-auto text-lg font-bold">
			<ul class="flex gap-8">
				<a href="/"><li class="hover:underline">Workspace</li></a>
				<a href="/"
					><li class="flex gap-1 items-center hover:underline">
						Locations <svg
							xmlns="http://www.w3.org/2000/svg"
							class="h-5 w-5"
							fill="none"
							viewBox="0 0 24 24"
							stroke="currentColor"
							stroke-width="2.4"
						>
							<path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7" />
						</svg>
					</li></a
				>
				<a href="/"><li class="hover:underline">About</li></a>
				<a href="/"><li class="hover:underline">Contact</li></a>
			</ul>
		</div>
		<div class="mr-[3%] ">
			<button
				class="text-green-400 hover:text-green-500 text-lg border-2 border-green-400 hover:border-green-500 rounded-full py-2 px-7 transition-all"
				>Log in</button
			>
		</div>
	</div>
</template>
