<script>
	import Icon from '$lib/components/icon.svelte';
	import Hero from '$lib/components/layout/hero.svelte';
	import Button from '$lib/components/button.svelte';
	import Container from '$lib/components/layout/container.svelte';
	import Question from '$lib/components/cards/question.svelte';
</script>

<Hero>
	<div slot="content">
		<p class="mb-4 text-2xl font-bold lg:text-4xl">Frequently Asked Questions</p>
		<p class="max-w-prose">
			Fermentum dui faucibus in ornare quam viverra orci. Non diam phasellus vestibulum lorem
			sed risus ultricies tristique nulla.
		</p>
	</div>
	<div slot="modal" class="bg-gradient-to-b from-transparent from-50% to-white to-50%">
		<Container>
			<div class="mx-auto mb-3 w-full max-w-[800px] rounded bg-white p-2 shadow-lg">
				<div class="grid grid-rows-3 gap-2 md:grid-cols-4 md:grid-rows-1">
					<div class="flex items-center gap-2 p-2 md:mx-auto">
						<Icon icon="calendar_month" weight={500} />
						<p class="font-semibold">21 August 2024</p>
					</div>
					<div class="md:flex md:border-x-2 md:border-slate-200">
						<div class="flex items-center gap-2 p-2 md:mx-auto">
							<Icon icon="artist" weight={500} />
							<p class="font-semibold">100 Artists</p>
						</div>
					</div>
					<div class="flex items-center gap-2 p-2 md:mx-auto">
						<Icon icon="family_restroom" weight={500} />
						<p class="font-semibold">Family Friendly</p>
					</div>
					<div class="mx-auto w-full text-center">
						<Button
							classes="block bg-sky-500 p-3 font-bold text-white shadow-[rgba(50,_50,_105,_0.15)_0px_2px_5px_0px,_rgba(0,_0,_0,_0.05)_0px_1px_1px_0px]"
						>
							Get Tickets Now
						</Button>
					</div>
				</div>
			</div>
		</Container>
	</div>
</Hero>

<Container>
	<div class="grid gap-4 md:grid-cols-2 lg:grid-cols-3">
		<Question question="Question goes here?" answer="This is the answer to the question." />
		<Question question="Question goes here?" answer="This is the answer to the question." />
	</div>
</Container>