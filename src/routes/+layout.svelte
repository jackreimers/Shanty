<script lang="ts">
	import '../app.css';
	import Header from '$lib/components/header.svelte';
</script>

<div class="h-screen">
	<div class="flex min-h-full flex-col">
		<Header />

		<div class="mb-20 flex-1">
			<slot />
		</div>
	</div>
</div>
