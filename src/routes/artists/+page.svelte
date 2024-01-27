<script lang="ts">
	import Hero from '$lib/components/layout/hero.svelte';
	import Container from '$lib/components/layout/container.svelte';
	import ArtistCard from '$lib/components/artist-card.svelte';
	import Icon from '$lib/components/icon.svelte';
</script>

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
	<div class="grid gap-4">
		<ArtistCard
			name="Artist Name"
			description="Fermentum dui faucibus in ornare quam viverra orci. Non diam phasellus vestibulum lorem sed risus ultricies tristique nulla."
		/>
	</div>
</Container>
