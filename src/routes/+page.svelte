<script>
	import Countdown from '$lib/components/countdown.svelte';
	import Button from '$lib/components/button.svelte';
	import Icon from '$lib/components/icon.svelte';
</script>

<div class="flex flex-col gap-3">
	<section class="rounded bg-gray-50 p-2.5">
		<Countdown />
	</section>

	<section class="mx-auto w-full text-center">
		<Button classes="inline-block w-full border border-gray-500 px-5 py-3 font-semibold">
			Get Tickets Now
			<Icon icon="open_in_new" />
		</Button>
	</section>

	<section class="rounded bg-gray-50 p-2.5">
		<h1 class="font-semibold">Welcome!</h1>
		<p>
			Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
			incididunt ut labore et dolore magna aliqua.
		</p>
	</section>
</div>
<!--
-->
