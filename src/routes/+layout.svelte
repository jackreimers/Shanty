<script lang="ts">
	import '../app.css';

	import Header from '$lib/components/header.svelte';
	import Footer from '$lib/components/layout/footer.svelte';
</script>

<div class="h-screen">
	<div class="flex min-h-full flex-col">
		<Header />

		<div class="mb-20 flex-1">
			<slot />
		</div>

		<Footer />
	</div>
</div>
