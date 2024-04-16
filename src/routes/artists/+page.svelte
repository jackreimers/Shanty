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
		<p class="header mb-4 text-2xl font-bold lg:text-4xl">Festival Lineup</p>
		<p class="max-w-prose">
			Set sail on a musical journey through the ages with our Festival Lineup, where every
			shanty spins a tale of the boundless sea and the rugged sailors who call it home.
		</p>
	</div>
</Hero>

<Container>
	<div class="grid gap-4 min-[500px]:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4">
		<ArtistCard name="Salty Sirens" description="Region" />
		<ArtistCard name="Rum Skull" description="Region" />
		<ArtistCard name="Foc's'l Firkins" description="Region" />
		<ArtistCard name="Lost Quays" description="Region" />
		<ArtistCard name="She Shants" description="Region" />
		<ArtistCard name="The Anchormen" description="Region" />
		<ArtistCard name="Salty Sea Dogs" description="Region" />
		<ArtistCard name="The Rust Buckets" description="Region" />
		<ArtistCard name="Boodji Creek" description="Region" />
		<ArtistCard name="Duality" description="Region" />
		<ArtistCard name="Sunset Coast Shanty Crew" description="Region" />
		<ArtistCard name="Lee Shore Songs" description="Region" />
		<ArtistCard name="Spirit of Alba" description="Region" />
		<ArtistCard name="Amity Rogues" description="Region" />
		<ArtistCard name="Poets Breakfast" description="Region" />
		<ArtistCard name="Rum Jungle" description="Region" />
		<ArtistCard name="The Salt Lake Shantymen" description="Region" />
		<ArtistCard name="The Mandurah Mariners" description="Region" />
		<ArtistCard name="Stigwood" description="Region" />
		<ArtistCard name="Michael Ward Trio" description="Region" />
		<ArtistCard name="Irish Session" description="Region" />
		<ArtistCard name="The Dunn Bay Wailers" description="Region" />
		<ArtistCard name="Mucky Duck Bush Band" description="Region" />
		<ArtistCard name="Warralakin" description="Region" />
		<ArtistCard name="Peter Budgen" description="Region" />
	</div>
</Container>
