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

<div class="bg-sky-100">
	<div class="container mx-auto px-3 py-36">
		<p class="mb-4 text-4xl font-bold">
			Lorem ipsum dolor sit amet, consectetur adipiscing elit.
		</p>
		<p class="max-w-prose">
			Fermentum dui faucibus in ornare quam viverra orci. Non diam phasellus vestibulum lorem
			sed risus ultricies tristique nulla. Malesuada proin libero nunc consequat interdum
			varius sit amet. Pharetra pharetra massa massa ultricies mi. Est velit egestas dui id
			ornare arcu odio ut sem. At augue eget arcu dictum varius duis.
		</p>
	</div>
</div>
<!--
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
-->
