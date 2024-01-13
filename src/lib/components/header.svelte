<script lang="ts">
	import Icon from '$lib/components/icon.svelte';
	import Button from '$lib/components/button.svelte';
</script>

<header class="border-b border-gray-700 py-3 md:py-5">
	<div class="container mx-auto px-3 sm:flex">
		<div class="flex flex-1 items-center">
			<div>
				<h1 class="text-2xl font-bold md:mb-1 md:text-4xl">Bunbury Sea Shanty Festival</h1>
				<p>Tagline about the event</p>
			</div>
		</div>
		<div class="hidden items-center sm:flex">
			<Button classes="border border-gray-700 px-3.5 py-2.5 font-semibold leading-none">
				Tickets
				<Icon icon="open_in_new" classes="text-base" />
			</Button>
		</div>
	</div>
</header>
