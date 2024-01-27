<script>
	import Hero from '$lib/components/layout/hero.svelte';
	import Container from '$lib/components/layout/container.svelte';

	import Button from '$lib/components/button.svelte';
	import Icon from '$lib/components/icon.svelte';
</script>

<Hero bottomBuffer={true}>
	<p class="mb-4 text-2xl font-bold lg:text-4xl">Bunbury's Newest Folk Music Event</p>
	<p class="max-w-prose">
		Fermentum dui faucibus in ornare quam viverra orci. Non diam phasellus vestibulum lorem sed
		risus ultricies tristique nulla.
	</p>
</Hero>

<Container>
	<div
		class="mx-auto mb-3 mt-[-64px] w-full rounded bg-white p-2 shadow-[rgba(50,_50,_105,_0.15)_0px_2px_5px_0px,_rgba(0,_0,_0,_0.05)_0px_1px_1px_0px] sm:w-3/4 sm:min-w-[600px] lg:w-1/2"
	>
		<div class="grid grid-rows-3 gap-2 md:grid-cols-3 md:grid-rows-1">
			<div class="flex items-center gap-2 p-2 md:mx-auto">
				<Icon icon="artist" weight={500} />
				<p class="font-semibold">10 Artists</p>
			</div>
			<div class="md:flex md:border-x-2 md:border-gray-200">
				<div class="flex items-center gap-2 p-2 md:mx-auto">
					<Icon icon="calendar_month" weight={500} />
					<p class="font-semibold">1 January 1970</p>
				</div>
			</div>
			<div class="flex items-center gap-2 p-2 md:mx-auto">
				<Icon icon="question_mark" weight={500} />
				<p class="font-semibold">Something Else</p>
			</div>
		</div>
	</div>
	<!--
	<div class="mx-auto mb-12 w-full text-center sm:w-3/4 sm:min-w-[600px] lg:w-1/2">
		<Button
			classes="block bg-sky-200 p-3 font-bold shadow-[rgba(50,_50,_105,_0.15)_0px_2px_5px_0px,_rgba(0,_0,_0,_0.05)_0px_1px_1px_0px]"
		>
			Get Tickets Now
		</Button>
	</div>
-->
	<div class="flex flex-col gap-8">
		<div class="flex-1">
			<p class="mb-2 font-semibold">About</p>
			<p>
				Fermentum dui faucibus in ornare quam viverra orci. Non diam phasellus vestibulum
				lorem sed risus ultricies tristique nulla. Malesuada proin libero nunc consequat
				interdum varius sit amet. Pharetra pharetra massa massa ultricies mi. Est velit
				egestas dui id ornare arcu odio ut sem. At augue eget arcu dictum varius duis.
			</p>
		</div>
		<div class="flex-1">
			<p class="mb-2 font-semibold">Artists</p>
			<p>
				Fermentum dui faucibus in ornare quam viverra orci. Non diam phasellus vestibulum
				lorem sed risus ultricies tristique nulla. Malesuada proin libero nunc consequat
				interdum varius sit amet. Pharetra pharetra massa massa ultricies mi. Est velit
				egestas dui id ornare arcu odio ut sem. At augue eget arcu dictum varius duis.
			</p>
		</div>
		<div class="flex-1">
			<p class="mb-2 text-2xl font-medium">Tickets</p>
			<p>
				Fermentum dui faucibus in ornare quam viverra orci. Non diam phasellus vestibulum
				lorem sed risus ultricies tristique nulla. Malesuada proin libero nunc consequat
				interdum varius sit amet. Pharetra pharetra massa massa ultricies mi. Est velit
				egestas dui id ornare arcu odio ut sem. At augue eget arcu dictum varius duis.
			</p>
		</div>
		<div class="flex-1">
			<p class="mb-2 font-semibold">Merchandise</p>
			<p>
				Fermentum dui faucibus in ornare quam viverra orci. Non diam phasellus vestibulum
				lorem sed risus ultricies tristique nulla. Malesuada proin libero nunc consequat
				interdum varius sit amet. Pharetra pharetra massa massa ultricies mi. Est velit
				egestas dui id ornare arcu odio ut sem. At augue eget arcu dictum varius duis.
			</p>
		</div>
	</div>
</Container>
