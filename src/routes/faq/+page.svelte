<script>
	import Hero from '$lib/components/layout/hero.svelte';
	import Container from '$lib/components/layout/container.svelte';
	import Accordian from '$lib/components/elements/accordian.svelte';
</script>

<svelte:head>
	<title>Bunbury Sea Shanty Festival | FAQ</title>
</svelte:head>

<Hero>
	<div slot="content">
		<p class="mb-4 text-2xl font-bold lg:text-4xl">Frequently Asked Questions</p>
		<p class="max-w-prose">
			Fermentum dui faucibus in ornare quam viverra orci. Non diam phasellus vestibulum lorem
			sed risus ultricies tristique nulla.
		</p>
	</div>
</Hero>

<Container>
	<div class="flex w-full flex-col gap-4">
		<Accordian>
			<p slot="title">What is this question?</p>
		</Accordian>
		<Accordian>
			<p slot="title">What about this question?</p>
		</Accordian>
	</div>
</Container>
