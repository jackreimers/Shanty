<script lang="ts">
	import Hero from '$lib/components/layout/hero.svelte';
	import Container from '$lib/components/layout/container.svelte';
</script>

<Hero>
	<div slot="content">
		<p class="header text-2xl font-bold lg:text-4xl">Success!</p>
	</div>
</Hero>

<Container>
	<p>Thanks for contacting us, we will get back to you soon!</p>
</Container>
