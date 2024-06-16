<script>
	import Icon from '$lib/components/icon.svelte';
	import Hero from '$lib/components/layout/hero.svelte';
	import Button from '$lib/components/button.svelte';
	import Container from '$lib/components/layout/container.svelte';
	import SectionCard from '$lib/components/layout/section-card.svelte';
	import SectionHeader from '$lib/components/layout/section-header.svelte';
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
	<div class="flex flex-col gap-6">
		<SectionCard>
			<SectionHeader title="Bunbury Mission To Seafarers" icon="location_on" />
			<div class="flex gap-4">
				<div class="flex-1 rounded bg-white p-2">
					<img
						src="/images/seafarermission.jpg"
						alt="Bunbury Mission to Seafarers Logo"
						class="mx-auto max-h-[200px]"
					/>
				</div>
				<div class="flex-1">
					<p><span class="font-semibold">Address:</span> 17 Victoria St, Bunbury</p>
				</div>
			</div>
		</SectionCard>
		<SectionCard>
			<SectionHeader title="Froth Craft Brewery" icon="location_on" />
			<div class="flex gap-4">
				<div class="flex-1 rounded bg-white p-2">
					<img
						src="/images/froth.jpg"
						alt="Froth Craft Brewery Logo"
						class="mx-auto max-h-[200px]"
					/>
				</div>
				<div class="flex-1">
					<p><span class="font-semibold">Address:</span> 12 Victoria St, Bunbury</p>
				</div>
			</div>
		</SectionCard>
		<SectionCard>
			<SectionHeader title="Koombana Bay Sailing Club" icon="location_on" />
			<div class="flex gap-4">
				<div class="flex-1 rounded bg-white p-2">
					<img
						src="/images/koombanasailing.png"
						alt="Koombana Bay Sailing Club Logo"
						class="mx-auto max-h-[200px]"
					/>
				</div>
				<div class="flex-1">
					<p><span class="font-semibold">Address:</span> Anchorage Cv, Bunbury</p>
				</div>
			</div>
		</SectionCard>
		<SectionCard>
			<SectionHeader
				title="Bunbury Geographe Seniors and Community Centre"
				icon="location_on"
			/>
			<div class="flex gap-4">
				<div class="flex-1 rounded bg-white p-2">
					<img
						src="/images/bgscc.jpeg"
						alt="Koombana Bay Sailing Club Logo"
						class="mx-auto max-h-[200px]"
					/>
				</div>
				<div class="flex-1">
					<p><span class="font-semibold">Address:</span> 1 Stirling St, Bunbury</p>
				</div>
			</div>
		</SectionCard>
	</div>
</Container>
