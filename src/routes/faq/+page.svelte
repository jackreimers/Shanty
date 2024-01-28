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
</Hero>

<Container>
	<div class="grid gap-4 md:grid-cols-2 lg:grid-cols-3">
		<Question question="Question goes here?" answer="This is the answer to the question." />
		<Question question="Question goes here?" answer="This is the answer to the question." />
	</div>
</Container>
