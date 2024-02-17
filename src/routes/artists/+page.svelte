<script lang="ts">
	import Hero from '$lib/components/layout/hero.svelte';
	import Container from '$lib/components/layout/container.svelte';
	import ArtistCard from '$lib/components/artist-card.svelte';
</script>

<svelte:head>
	<title>Bunbury Sea Shanty Festival | Artists</title>
</svelte:head>

<Hero>
	<div slot="content">
		<p class="mb-4 text-2xl font-bold lg:text-4xl">Festival Lineup</p>
		<p class="max-w-prose">
			Fermentum dui faucibus in ornare quam viverra orci. Non diam phasellus vestibulum lorem
			sed risus ultricies tristique nulla.
		</p>
	</div>
</Hero>

<Container>
	<div class="grid gap-4 min-[500px]:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4">
		<ArtistCard name="Artist Name" description="Region" />
		<ArtistCard name="Artist Name" description="Region" />
		<ArtistCard name="Artist Name" description="Region" />
		<ArtistCard name="Artist Name" description="Region" />
	</div>
</Container>
