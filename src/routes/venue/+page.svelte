<script>
	import Icon from '$lib/components/icon.svelte';
	import Hero from '$lib/components/layout/hero.svelte';
	import Button from '$lib/components/button.svelte';
	import Container from '$lib/components/layout/container.svelte';
	import Question from '$lib/components/cards/question.svelte';
</script>

<Hero>
	<div slot="content">
		<p class="mb-4 text-2xl font-bold lg:text-4xl">Venue Details</p>
		<p class="max-w-prose">
			Fermentum dui faucibus in ornare quam viverra orci. Non diam phasellus vestibulum lorem
			sed risus ultricies tristique nulla.
		</p>
	</div>
</Hero>

<Container>
	<div class="grid gap-4 lg:grid-cols-3">
		<div class="rounded bg-gray-100 p-3.5 lg:col-span-2">
			<div class="rounded bg-white py-20 text-center shadow-inner">
				<Icon icon="image" classes="text-6xl text-gray-400" />
			</div>
		</div>
		<div class="flex flex-col rounded bg-gray-100 p-3.5">
			<p class="mb-1 font-semibold">Venue Address</p>
			<p class="mb-6 flex-1">
				Fermentum dui faucibus in ornare quam viverra orci. Non diam phasellus vestibulum
				lorem sed risus ultricies tristique nulla. Malesuada proin libero nunc consequat
				interdum varius sit amet.
			</p>
			<div>
				<Button
					classes="block bg-sky-500 px-5 py-3 text-center font-bold text-white md:inline-block lg:block"
					>Open in Google Maps</Button
				>
			</div>
		</div>
	</div>
</Container>
