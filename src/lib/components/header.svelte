<script lang="ts">
	import Icon from '$lib/components/icon.svelte';
	import Button from '$lib/components/button.svelte';

	let open: boolean = false;
</script>

<svelte:head>
	<title>Bunbury Sea Shanty Festival</title>
</svelte:head>

<header class="z-10 shadow-md">
	<div class="container mx-auto flex px-3">
		<div class="flex-1">
			<h1 class="mb-1 py-6 text-2xl font-semibold leading-none">
				Bunbury Sea Shanty Festival
			</h1>
			<!--
			<Button
				onClick={() => (open = !open)}
				classes="border border-gray-300 px-2 py-1 font-medium"
			>
				<Icon icon="menu" weight={400} />
				Menu
			</Button>
			-->
		</div>
		<div class="flex gap-4 text-center">
			<Button
				classes="flex items-center rounded-none border-b-4 border-gray-500 px-4 font-semibold"
			>
				Overview
			</Button>
			<Button
				href="/artists"
				classes="flex items-center rounded-none border-b-4 border-transparent px-4 font-semibold hover:border-gray-500"
			>
				Lineup
			</Button>
			<Button
				classes="flex items-center rounded-none border-b-4 border-transparent px-4 font-semibold hover:border-gray-500"
			>
				FAQ
			</Button>
		</div>
	</div>
</header>
