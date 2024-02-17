<script>
	import Hero from '$lib/components/layout/hero.svelte';
	import Container from '$lib/components/layout/container.svelte';
</script>

<Hero>
	<div slot="content">
		<p class="mb-4 text-2xl font-bold lg:text-4xl">Bunbury's Newest Folk Music Event</p>
		<p class="max-w-prose">
			Fermentum dui faucibus in ornare quam viverra orci. Non diam phasellus vestibulum lorem
			sed risus ultricies tristique nulla.
		</p>
	</div>
</Hero>

<Container>
	<div class="flex flex-col gap-4 md:flex-row">
		<div
			class="block min-h-[150px] flex-1 rounded bg-[url('/images/bunbury-waves.jpg')] bg-cover bg-center"
		/>
		<div class="flex-[2] rounded bg-gray-100 p-4 md:p-6">
			<h2 class="mb-2 text-2xl font-semibold">About The Festival</h2>
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
</Container>
