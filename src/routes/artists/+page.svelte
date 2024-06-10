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
	<div class="mb-4 grid gap-4 min-[500px]:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4">
		<ArtistCard name="Lost Quays" imageUrl="/images/bands/lost-quays.jpeg" />
		<ArtistCard name="Salty Sirens" imageUrl="/images/bands/salty-sirens.jpeg" />
		<ArtistCard name="Foc's'l Firkins" imageUrl="/images/bands/focsle-firkins.jpeg" />
		<ArtistCard name="Rum Skull" imageUrl="/images/bands/rumskull.jpeg" />
	</div>
	<div class="grid gap-4 min-[500px]:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4">
		<ArtistCard name="She Shants" />
		<ArtistCard name="The Anchormen" />
		<ArtistCard name="Salty Sea Dogs" />
		<ArtistCard name="The Rust Buckets" />
		<ArtistCard name="Boodji Creek" />
		<ArtistCard name="Duality" />
		<ArtistCard name="Sunset Coast Shanty Crew" />
		<ArtistCard name="Lee Shore Songs" />
		<ArtistCard name="Spirit of Alba" />
		<ArtistCard name="Amity Rogues" />
		<ArtistCard name="Poets Breakfast" />
		<ArtistCard name="Rum Jungle" />
		<ArtistCard name="The Salt Lake Shantymen" />
		<ArtistCard name="The Mandurah Mariners" />
		<ArtistCard name="Stigwood" />
		<ArtistCard name="Michael Ward Trio" />
		<ArtistCard name="Irish Session" />
		<ArtistCard name="The Dunn Bay Wailers" />
		<ArtistCard name="Mucky Duck Bush Band" />
		<ArtistCard name="Warralakin" />
		<ArtistCard name="Peter Budgen" />
	</div>
</Container>
