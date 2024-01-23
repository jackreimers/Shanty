<script lang="ts">
	import '../app.css';
	import Header from '$lib/components/header.svelte';
</script>

<div class="h-screen">
	<div class="flex min-h-full flex-col">
		<Header />

		<div class="container mx-auto flex-1 px-2.5">
			<slot />
		</div>
	</div>
</div>
