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
			<div class="grid gap-4 min-[500px]:grid-cols-2 lg:grid-cols-3">
				<ArtistCard
					name="Amity Rogues"
					description="Formerly known as ‘The Shantylillies’, the ‘Amity Rogues’ have gone through a bit of a transition in recent times.  Drastically reduced in numbers, but not in shanty spirit and welcoming a male human into their fold, they are ready to continue on our shanty journey."
				/>
				<ArtistCard
					name="Boodji Creek"
					description="This five-piece acoustic America, Bluegrass and Old-Timey Band perform boot-tapping live music to venues across Australia’s' South West, from halls, to pubs, to backyard jam sessions!"
				/>
				<ArtistCard
					name="Duality"
					description="This Perth-based folk duo is based in Perth. John has played in folk clubs and festivals in the UK and Australia. Joe works in schools as a guitar teacher and studied classical guitar at WAAPA."
				/>
				<ArtistCard
					name="Lee Shore Songs"
					description="Lee Shore not only does sea shanties, but other songs of the sea and ballads in the traditional folk style."
				/>
				<ArtistCard
					name="Michael Ward Trio"
					description="Raised on the salty coastal swamplands of Stratham in regional WA, Michael delivers his fusion of gritty blues, folk and alt country with a supercharged energy whenever he's on stage. An unforgettably unique show."
				/>
				<ArtistCard
					name="Mucky Duck Bush Band"
					description="They've been around for a long, long time...Since 1974, the ‘Duck’ has been performing its unique brand of Australian folk songs and dance to audiences large and small at festivals, community & corporate events and schools across Australia and overseas."
				/>
				<ArtistCard name="Peter Budgen" />
				<ArtistCard
					name="Rum Jungle"
					description="This maritime music group hails from Geraldton, Western Australia. The name, Rum Jungle, conjures up visions of a tropical rain forest full of fiesty pirates, fighting over the latest treasure haul whilst a nearby rum still bubbles away."
				/>
				<ArtistCard
					name="Salty Sea Dogs"
					description="From what started as Monday nights in the boat shed with some mates and a few beers the SSD have grown into a powerhouse of togetherness relying on friendship and strength in diversity to hone their sound. First appearing at Denmark’s ‘Festival of the Voice’ in 2021, the SSD have gone on to appear at the Albany Shanty Fest multiple times; toured the Great Southern; and released their first EP titled ‘Tiger Snake Alley’ in 2023."
				/>
				<ArtistCard
					name="She Shants"
					description="She Shants are slightly subversive, sometimes sweet. They draw repertoire from traditional and original songs of waiting, loss, adventure and a fascination of sea creatures."
				/>
				<ArtistCard
					name="Spirit of Alba"
					description="Their exquisitely rugged yet refined blend of fiddle, guitar, border pipes, whistle and bodhran has been wowing audiences across Perth since 2020. With no shortage of energy when it comes to delivering powerful entrancing instrumentals, Spirit of Alba leave audiences breathless."
				/>
				<ArtistCard name="Stigwood" />
				<ArtistCard
					name="Sunset Coast Shanty Crew"
					description="Inspired by the growing shanty scene in WA, the Sunset Coast Shanty Crew formed in late June 2023 making them WA’s newest shanty group. They initially spent time below deck in private rehearsal, but have since set sail into the local community and established a home port where they gather each week to sail around the globe through shanties and other nautical numbers."
				/>
				<ArtistCard name="The Anchormen" />
				<ArtistCard
					name="The Dunn Bay Wailers"
					description="A bunch of lads (and often lasses) from Dunsborough WA that get together and sing sea shanties loudly."
				/>
				<ArtistCard name="The Mandurah Mariners" />
				<ArtistCard
					name="The RUSTBUCKETS"
					description="The RUSTBUCKETS are four veterans of the Western Australian acoustic music scene. With roots delving into bands that began in the 60's, their decades of experience combine to bring uplifting country blues, jugband, hokum and swing tunes delivered with masterful playing and humorous stories."
				/>
				<ArtistCard
					name="The Salt Lake Shantymen"
					description="The lads who are The Salt Lake Shantymen have variously been described as ‘Howling Hooligans’, ‘Ranting Rapscallions’ and even (gasp!) ‘Shabbaroon Shantymen’ (look it up). The Shantymen spend their days roving (actually, looking for) the docks of the Goldfields, singing about the good old days to anyone who’ll listen. Songs of the sea don't get any saltier than this. "
				/>
				<ArtistCard name="Warralakin" />
			</div>
		</SectionCard>
		<SectionCard>
			<SectionHeader title="Activities" icon="celebration" />
			<div class="grid gap-4 min-[500px]:grid-cols-2 lg:grid-cols-3">
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
