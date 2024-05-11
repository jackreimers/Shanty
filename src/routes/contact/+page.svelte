<script>
	import Container from '$lib/components/layout/container.svelte';
	import Hero from '$lib/components/layout/hero.svelte';
</script>

<Hero>
	<div slot="content">
		<p class="header text-2xl font-bold lg:text-4xl">Contact</p>
	</div>
</Hero>

<Container>
	<form action="https://email.bunburyshantyfest.au" method="post" class="flex max-w-lg flex-col">
		<label for="text" class="font-medium">Your Name <span class="text-red-500">*</span></label>
		<input type="text" name="name" required class="mb-4 rounded border border-gray-500 p-2" />

		<label for="email" class="font-medium">Your Email <span class="text-red-500">*</span></label
		>
		<input type="email" name="email" required class="mb-4 rounded border border-gray-500 p-2" />

		<label for="message" class="font-medium">Your Message</label>
		<input type="text" name="message" class="mb-4 rounded border border-gray-500 p-2" />

		<input
			type="submit"
			class="cursor-pointer rounded bg-sky-600 p-3 font-bold text-white shadow-[rgba(50,_50,_105,_0.15)_0px_2px_5px_0px,_rgba(0,_0,_0,_0.05)_0px_1px_1px_0px]"
		/>
	</form>
</Container>
