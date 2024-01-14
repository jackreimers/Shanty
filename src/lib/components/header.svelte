<script lang="ts">
	import Icon from '$lib/components/icon.svelte';
	import Button from '$lib/components/button.svelte';

	let open: boolean = false;
</script>

<svelte:head>
	<title>Bunbury Sea Shanty Festival</title>
</svelte:head>

<header class="border-b border-gray-700 py-3">
	<div class="container mx-auto px-3">
		<div class="items-center text-center">
			<h1 class="mb-2 text-2xl font-bold md:text-4xl">Bunbury Sea Shanty Festival</h1>
			<Button
				onClick={() => (open = !open)}
				classes="border border-gray-300 px-2 py-1 font-medium"
			>
				<Icon icon="menu" weight={400} />
				Menu
			</Button>
		</div>
	</div>
</header>
<div class="overflow-hidden" class:h-0={!open}>
	<div class="border-b border-gray-700">
		<div class="m-3">
			<div
				class="mx-auto grid max-w-3xl grid-cols-2 gap-3 text-center sm:grid-cols-3 md:grid-cols-4"
			>
				<Button classes="border border-gray-300 p-2">
					<Icon icon="open_in_new" weight={400} />
					<p class="font-medium">Tickets</p>
				</Button>
				<Button classes="border border-gray-300 p-2">
					<Icon icon="artist" weight={400} />
					<p class="font-medium">Lineup</p>
				</Button>
				<Button classes="border border-gray-300 p-2">
					<Icon icon="apparel" weight={400} />
					<p class="font-medium">Merchandise</p>
				</Button>
				<Button classes="border border-gray-300 p-2">
					<Icon icon="near_me" weight={400} />
					<p class="font-medium">Venue</p>
				</Button>
				<Button classes="border border-gray-300 p-2">
					<Icon icon="volunteer_activism" weight={400} />
					<p class="font-medium">Volunteering</p>
				</Button>
				<Button classes="border border-gray-300 p-2">
					<Icon icon="ad" weight={400} />
					<p class="font-medium">Advertisers</p>
				</Button>
				<Button classes="border border-gray-300 p-2">
					<Icon icon="payments" weight={400} />
					<p class="font-medium">Sponsors</p>
				</Button>
				<Button classes="border border-gray-300 p-2">
					<Icon icon="help" weight={400} />
					<p class="font-medium">FAQ</p>
				</Button>
			</div>
		</div>
	</div>
</div>
