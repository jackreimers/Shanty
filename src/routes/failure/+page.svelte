<script lang="ts">
	import Hero from '$lib/components/layout/hero.svelte';
	import Container from '$lib/components/layout/container.svelte';
</script>

<Hero>
	<div slot="content">
		<p class="header text-2xl font-bold lg:text-4xl">Oops!</p>
	</div>
</Hero>

<Container>
	<p>Something went wrong, please try again.</p>
	<p>Contact us directly at contact@bunburyshantyfest.au if the issue persists.</p>
</Container>
