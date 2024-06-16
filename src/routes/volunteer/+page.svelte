<script>
	import Hero from '$lib/components/layout/hero.svelte';
	import Container from '$lib/components/layout/container.svelte';
</script>

<svelte:head>
	<title>Bunbury Sea Shanty Festival | Volunteering</title>
</svelte:head>

<Hero>
	<div slot="content">
		<p class="header text-2xl font-bold lg:text-4xl">Volunteering</p>
	</div>
</Hero>

<Container>
	<p class="mb-2">
		We're looking for enthusiastic volunteers to join us for the upcoming Bunbury Sea Shanty
		Festival! As a volunteer, you'll have the opportunity to be part of an amazing team and
		contribute to the success of the festival.
	</p>

	<p class="mb-2">Roles include (but are not limited to):</p>
	<ul class="mb-2 ml-6 list-decimal">
		<li>Front of House</li>
		<li>MC</li>
		<li>Tech Support (experience desired)</li>
		<li>Retail / Merchandise.</li>
	</ul>

	<p class="mb-2">
		Each volunteer will receive a free weekend pass (after 6 hours of volunteering) and a
		t-shirt.
	</p>

	<p class="mb-2">
		If you're interested in being part of this exciting event, please email us at
		contact@bunburyshantyfest.au
	</p>

	<p>Note: Please also refer to the FAQ section of the website, for more information</p>
</Container>
