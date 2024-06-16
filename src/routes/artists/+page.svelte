<script lang="ts">
	import Hero from '$lib/components/layout/hero.svelte';
	import Container from '$lib/components/layout/container.svelte';
	import ArtistCard from '$lib/components/artist-card.svelte';
	import SectionCard from '$lib/components/layout/section-card.svelte';
	import SectionHeader from '$lib/components/layout/section-header.svelte';
	import Icon from '$lib/components/icon.svelte';
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
	<div class="flex flex-col gap-6">
		<SectionCard>
			<SectionHeader title="Bands" icon="music_note" />
			<div class="grid gap-4 min-[500px]:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4">
				<ArtistCard
					name="Lost Quays"
					description="Hailing from the port of Fremantle, the Lost Quays is an eight-piece shanty band. Their repertoire includes many of the standards of the shanty world, plus a number of originals focussing on stories of the shipwrecks and daring sailors around the coast of WA and beyond."
					imageUrl="/images/bands/lost-quays.jpeg"
				/>

				<ArtistCard
					name="Salty Sirens"
					description="The Salty Sirens share traditional sea shanties, she shanties, and sea songs with a modern, queer twist. Accompanied by accordion ‘Moni’ and occasionally backed by a ragtag band of Irate Pirates, The Salty Sirens share tales of hard work, daring adventure, defiance and debauchery. These aren’t your Grandpa’s sea shanties!"
					imageUrl="/images/bands/salty-sirens.jpeg"
				/>
				<ArtistCard
					name="Foc's'l Firkins"
					description="The Fo'c's'le Firkins are one of Australia's oldest a capella shanty groups that formed in Perth for the 1985 National Folk Festival. In recent years, there has been a recent global revival of interest in traditional shanty work songs from the Tall Ships era and the Firkins are proud to have been part of this ongoing folk tradition for nearly forty years. Experience the raw power of authentic traditional shanties and seafaring maritime songs with the original Fo’c’s’le Firkins."
					imageUrl="/images/bands/focsle-firkins.jpeg"
				/>
				<ArtistCard
					name="Rumskull"
					description="Infamous they are for whipping their crew into a frenzy, Rumskull bellow out the most rollicking sea shanties ever to rattle a pirate’s gold earring. Whose event will they shanghai next? Know only this: if your head be pounding, your dancing shoes be trampled and your singing voice be hoarse, it's likely you have run aground and gone down with the bad ship Rumskull."
					imageUrl="/images/bands/rumskull.jpeg"
				/>
			</div>
			<div class="my-4 text-center">
				<div
					class="inline-flex items-center gap-2 rounded bg-[rgb(53,98,108)] p-2 text-white"
				>
					<Icon icon="add" />
					<p class="mr-2 font-semibold">Plus many more great bands!</p>
				</div>
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
		</SectionCard>
		<SectionCard>
			<SectionHeader title="Activities" icon="celebration" />
			<div class="grid gap-4 min-[500px]:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4">
				<ArtistCard name="Bush Poets Breakfast" />
				<ArtistCard name="Folk Club" />
				<ArtistCard name="International Dance" />
				<ArtistCard name="Irish Session" />
				<ArtistCard name="Long Table Brunch" />
				<ArtistCard name="Sea Shanty Singing Workshop" />
				<ArtistCard name="Write Your Own Sea Shanty Competition" />
			</div>
		</SectionCard>
	</div>
</Container>
