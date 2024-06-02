<script>
	import Hero from '$lib/components/layout/hero.svelte';
	import Container from '$lib/components/layout/container.svelte';
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
	<div class="flex flex-col gap-4 md:flex-row">
		<div
			class="block min-h-[150px] flex-1 rounded bg-[url('/images/bunbury-waves.jpg')] bg-cover bg-center"
		/>
		<div class="flex-[2] rounded bg-gray-100 p-4 md:p-6">
			<h2 class="header mb-2 text-2xl font-semibold sm:text-3xl">About The Festival</h2>
			<p>
				Ahoy, mates! Welcome to the inaugural Bunbury Sea Shanty Festival, where the waves
				meet the melodies in Western Australia's charming coastal city Bunbury. Join us for
				a celebration of timeless maritime tunes against the backdrop of Bunbury's stunning
				shores and enchanting venues. Let's raise our voices and spirits in harmony as we
				honor the seafaring tradition with music, merriment, and memories to last a
				lifetime.
			</p>
		</div>
	</div>
	<div class="my-8 overflow-hidden rounded">
		<Button
			href="/program.pdf"
			classes="mb-2 inline-block rounded bg-sky-600 p-2 font-semibold text-white"
		>
			<Icon icon="download" />
			Download Program
		</Button>
		<img src="/images/program-1.jpg" />
		<img src="/images/program-2.jpg" />
	</div>
	<h2 class="header mb-2 mt-8 text-2xl font-semibold sm:text-3xl">Our Sponsors</h2>
	<div
		class="grid grid-cols-2 grid-rows-2 gap-4 rounded bg-gray-100 p-4 md:gap-8 md:p-6 lg:grid-cols-3 lg:grid-rows-1"
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
	<h2 class="header mb-2 mt-8 text-2xl font-semibold sm:text-3xl">Our Supporters</h2>
	<div class="grid grid-cols-2 gap-4 rounded bg-gray-100 p-4 md:gap-8 md:p-6 lg:grid-cols-3">
		<div class="flex items-center rounded bg-white p-4 md:p-6">
			<img src="/images/staidan.png" alt="St Aidan's Winery logo" />
		</div>
		<div class="flex items-center rounded bg-white p-4 md:p-6">
			<img src="/images/svitzer.png" alt="Svitzer Logo" />
		</div>
	</div>
</Container>
