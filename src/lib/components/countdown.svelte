<script lang="ts">
	import { onMount } from 'svelte';

	let date = new Date('2024-10-01T00:00:00').getTime();

	let days = 0;
	let hours = 0;
	let minutes = 0;
	let seconds = 0;

	onMount(() => {
		setInterval(() => {
			getTime();
		}, 1000);
	});

	function getTime() {
		const now = new Date().getTime();
		const distance = date - now;

		days = Math.floor(distance / (1000 * 60 * 60 * 24));
		hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
		minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
		seconds = Math.floor((distance % (1000 * 60)) / 1000);
	}
</script>

<div class="grid grid-cols-4 gap-2">
	<div class="flex flex-col gap-1 border border-gray-300 p-2 text-center">
		<p class="text-2xl leading-none">{days}</p>
		<p class="text-sm">Days</p>
	</div>
	<div class="flex flex-col gap-1 border border-gray-300 p-2 text-center">
		<p class="text-2xl leading-none">{hours}</p>
		<p class="text-sm">Hours</p>
	</div>
	<div class="flex flex-col gap-1 border border-gray-300 p-2 text-center">
		<p class="text-2xl leading-none">{minutes}</p>
		<p class="text-sm">Minutes</p>
	</div>
	<div class="flex flex-col gap-1 border border-gray-300 p-2 text-center">
		<p class="text-2xl leading-none">{seconds}</p>
		<p class="text-sm">Seconds</p>
	</div>
</div>
