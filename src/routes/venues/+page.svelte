<script>
	import Icon from '$lib/components/icon.svelte';
	import Hero from '$lib/components/layout/hero.svelte';
	import Button from '$lib/components/button.svelte';
	import Container from '$lib/components/layout/container.svelte';
</script>

<svelte:head>
	<title>Bunbury Sea Shanty Festival | Venues</title>
</svelte:head>

<Hero>
	<div slot="content">
		<p class="header text-2xl font-bold lg:text-4xl">Venue Details</p>
	</div>
</Hero>

<Container>
	<div class="mb-4 grid gap-4 lg:grid-cols-2">
		<div class="rounded bg-gray-100 p-3.5">
			<div class="rounded bg-white p-4 text-center shadow-inner">
				<img
					src="/images/seafarermission.jpg"
					alt="Bunbury Mission to Seafarers Logo"
					class="mx-auto max-h-[200px]"
				/>
			</div>
		</div>
		<div class="flex flex-col rounded bg-gray-100 p-3.5">
			<p class="mb-1 font-semibold sm:text-2xl">Bunbury Mission To Seafarers</p>
			<p class="mb-6 flex-1">17 Victoria St, Bunbury, WA, Australia, Western Australia</p>
		</div>
	</div>
	<div class="mb-4 grid gap-4 lg:grid-cols-2">
		<div class="rounded bg-gray-100 p-3.5">
			<div class="rounded bg-white p-4 text-center shadow-inner">
				<img
					src="/images/froth.jpg"
					alt="Froth Craft Brewery Logo"
					class="mx-auto max-h-[200px]"
				/>
			</div>
		</div>
		<div class="flex flex-col rounded bg-gray-100 p-3.5">
			<p class="mb-1 font-semibold sm:text-2xl">Froth Craft Brewery</p>
			<p class="mb-6 flex-1">12 Victoria St, Bunbury WA 6230</p>
		</div>
	</div>
	<div class="mb-4 grid gap-4 lg:grid-cols-2">
		<div class="rounded bg-gray-100 p-3.5">
			<div class="rounded bg-white p-4 text-center shadow-inner">
				<img
					src="/images/koombanasailing.png"
					alt="Koombana Bay Sailing Club Logo"
					class="mx-auto max-h-[200px]"
				/>
			</div>
		</div>
		<div class="flex flex-col rounded bg-gray-100 p-3.5">
			<p class="mb-1 font-semibold sm:text-2xl">Koombana Bay Sailing Club</p>
			<p class="mb-6 flex-1">Anchorage Cv, Bunbury, WA, Australia, Western Australia</p>
		</div>
	</div>
</Container>
