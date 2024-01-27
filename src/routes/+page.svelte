<script>
	import Hero from '$lib/components/layout/hero.svelte';

	import Button from '$lib/components/button.svelte';
	import Icon from '$lib/components/icon.svelte';
</script>

<Hero>
	<p class="mb-4 text-4xl font-bold">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
	<p class="max-w-prose">
		Fermentum dui faucibus in ornare quam viverra orci. Non diam phasellus vestibulum lorem sed
		risus ultricies tristique nulla. Malesuada proin libero nunc consequat interdum varius sit
		amet. Pharetra pharetra massa massa ultricies mi. Est velit egestas dui id ornare arcu odio
		ut sem. At augue eget arcu dictum varius duis.
	</p>
</Hero>

<div class="mx-auto mt-[-42px] w-1/2 rounded bg-white p-2 shadow-md">
	<div class="grid grid-cols-3 gap-2 text-center">
		<div class="flex items-center">
			<div class="mx-auto flex items-center gap-2 p-2">
				<Icon icon="calendar_month" weight={500} />
				<p class="font-semibold">1 January 1970</p>
			</div>
		</div>
		<div class="flex items-center border-x-2 border-gray-200">
			<div class="mx-auto flex items-center gap-2 p-2">
				<Icon icon="artist" weight={500} />
				<p class="font-semibold">10 Artists</p>
			</div>
		</div>
		<div class="flex items-center">
			<div class="mx-auto flex items-center gap-2 p-2">
				<Icon icon="question_mark" weight={500} />
				<p class="font-semibold">Something Else</p>
			</div>
		</div>
		<div class="col-span-3 mt-3">
			<Button classes="block bg-orange-100 p-3 font-bold">Get Tickets Now</Button>
		</div>
	</div>
</div>

<div class="mt-8 grid grid-cols-3 gap-4">
	<div class="border p-4">
		<p class="mb-2 text-2xl font-medium">Title Here</p>
		<p>
			Fermentum dui faucibus in ornare quam viverra orci. Non diam phasellus vestibulum lorem
			sed risus ultricies tristique nulla. Malesuada proin libero nunc consequat interdum
			varius sit amet. Pharetra pharetra massa massa ultricies mi. Est velit egestas dui id
			ornare arcu odio ut sem. At augue eget arcu dictum varius duis.
		</p>
	</div>
	<div class="border p-4">
		<p class="mb-2 text-2xl font-medium">Lineup</p>
		<p>
			Fermentum dui faucibus in ornare quam viverra orci. Non diam phasellus vestibulum lorem
			sed risus ultricies tristique nulla. Malesuada proin libero nunc consequat interdum
			varius sit amet. Pharetra pharetra massa massa ultricies mi. Est velit egestas dui id
			ornare arcu odio ut sem. At augue eget arcu dictum varius duis.
		</p>
	</div>
	<div class="border p-4">
		<p class="mb-2 text-2xl font-medium">Tickets</p>
		<p>
			Fermentum dui faucibus in ornare quam viverra orci. Non diam phasellus vestibulum lorem
			sed risus ultricies tristique nulla. Malesuada proin libero nunc consequat interdum
			varius sit amet. Pharetra pharetra massa massa ultricies mi. Est velit egestas dui id
			ornare arcu odio ut sem. At augue eget arcu dictum varius duis.
		</p>
	</div>
</div>
