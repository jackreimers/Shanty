<script lang="ts">
	import Icon from '$lib/components/icon.svelte';
	import Button from '$lib/components/button.svelte';
</script>

<header class="border-b border-gray-700 py-5">
	<div class="container mx-auto flex">
		<div class="flex flex-1 items-center">
			<div>
				<h1 class="mb-1 text-4xl font-bold">Bunbury Sea Shanty Festival</h1>
				<p>Tagline about the event</p>
			</div>
		</div>
		<div class="flex items-center">
			<Button classes="border border-gray-700 px-3.5 py-2.5 font-semibold leading-none">
				Tickets
				<Icon icon="open_in_new" classes="text-base" />
			</Button>
		</div>
	</div>
</header>
