<script>
	import Container from '$lib/components/layout/container.svelte';
	import Hero from '$lib/components/layout/hero.svelte';
	import SectionCard from '$lib/components/layout/section-card.svelte';
	import SectionHeader from '$lib/components/layout/section-header.svelte';
	import Icon from '$lib/components/icon.svelte';
	import Button from '$lib/components/button.svelte';
</script>

<Hero>
	<div slot="content">
		<p class="header mb-4 text-2xl font-bold lg:text-4xl">Bunbury's Newest Folk Music Event</p>
		<p class="max-w-prose">
			Set sail for a weekend of sea shanties and folk music at Bunbury's newest maritime
			extravaganza!
		</p>
	</div>
</Hero>

<Container>
	<div class="flex flex-col gap-6">
		<SectionCard>
			<SectionHeader title="About the Festival" icon="sailing" />
			<p>
				Ahoy, mates! Welcome to the inaugural Bunbury Sea Shanty Festival, where the waves
				meet the melodies in Western Australia's charming coastal city Bunbury. Join us for
				a celebration of timeless maritime tunes against the backdrop of Bunbury's stunning
				shores and enchanting venues. Let's raise our voices and spirits in harmony as we
				honour the seafaring tradition with music, merriment, and memories to last a
				lifetime.
			</p>
		</SectionCard>
		<SectionCard>
			<div class="mb-0 flex items-center">
				<SectionHeader title="Big Sing Booklet" icon="music_note" classes="!mb-0 flex-1" />
				<Button
					href="/sing-booklet.pdf"
					target="_blank"
					classes="inline-block rounded bg-sky-600 px-3.5 py-2.5 font-semibold text-white"
				>
					<span class="mx-1">Download</span>
					<Icon icon="download" />
				</Button>
			</div>
		</SectionCard>
		<SectionCard>
			<div class="mb-6 flex items-center">
				<SectionHeader title="Festival Program" icon="newsmode" classes="!mb-0 flex-1" />
				<Button
					href="/program.pdf"
					target="_blank"
					classes="inline-block rounded bg-sky-600 px-3.5 py-2.5 font-semibold text-white"
				>
					<span class="mx-1">Download</span>
					<Icon icon="download" />
				</Button>
			</div>
			<p class="mb-2.5">
				Below you will find information on the festival program, including the schedule for
				each day and the locations of the performances. You can download and print this
				program by clicking download and saving and printing the PDF file so you don't miss
				a thing.
			</p>
			<div class="flex flex-col gap-4">
				<img
					src="/images/program-1.jpg"
					alt="Page one of the festival program featuring band and event details."
					class="rounded"
				/>
				<img
					src="/images/program-2.jpg"
					alt="Page two of the festival program featuring a timetable and other details."
					class="rounded"
				/>
			</div>
		</SectionCard>
		<SectionCard>
			<SectionHeader title="Our Sponsors" icon="volunteer_activism" />
			<div
				class="grid grid-cols-2 grid-rows-2 gap-4 rounded bg-gray-100 md:gap-8 lg:grid-cols-3 lg:grid-rows-1"
			>
				<div class="flex items-center rounded bg-white p-4 md:p-6">
					<img src="/images/cob.png" alt="City of Bunbury logo" />
				</div>
				<div class="flex items-center rounded bg-white p-4 md:p-6">
					<img src="/images/southernports.png" alt="Southern Ports Logo" />
				</div>
				<div class="flex items-center rounded bg-white p-4 md:p-6">
					<img src="/images/aqwest.png" alt="Aqwest Logo" />
				</div>
			</div>
		</SectionCard>
		<SectionCard>
			<SectionHeader title="Our Supporters" icon="handshake" />
			<div class="grid grid-cols-2 gap-4 rounded bg-gray-100 md:gap-8 lg:grid-cols-3">
				<div class="flex items-center rounded bg-white p-4 md:p-6">
					<img src="/images/staidan.png" alt="St Aidan's Winery logo" />
				</div>
				<div class="flex items-center rounded bg-white p-4 md:p-6">
					<img src="/images/svitzer.png" alt="Svitzer Logo" />
				</div>
			</div>
		</SectionCard>
	</div>
</Container>
