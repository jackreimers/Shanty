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
	<div class="grid gap-6 md:grid-cols-2 lg:grid-cols-3">
		<div class="flex-1 rounded bg-gray-100 p-3.5">
			<h2 class="mb-2 font-semibold">About The Festival</h2>
			<p>
				Fermentum dui faucibus in ornare quam viverra orci. Non diam phasellus vestibulum
				lorem sed risus ultricies tristique nulla. Malesuada proin libero nunc consequat
				interdum varius sit amet. Pharetra pharetra massa massa ultricies mi. Est velit
				egestas dui id ornare arcu odio ut sem. At augue eget arcu dictum varius duis.
			</p>
		</div>
		<div class="flex-1 rounded bg-gray-100 p-3.5">
			<h2 class="mb-2 font-semibold">Artists</h2>
			<p>
				Fermentum dui faucibus in ornare quam viverra orci. Non diam phasellus vestibulum
				lorem sed risus ultricies tristique nulla. Malesuada proin libero nunc consequat
				interdum varius sit amet. Pharetra pharetra massa massa ultricies mi. Est velit
				egestas dui id ornare arcu odio ut sem. At augue eget arcu dictum varius duis.
			</p>
		</div>
	</div>
</Container>
