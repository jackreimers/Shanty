<script lang="ts">
	import Icon from '$lib/components/icon.svelte';

	export let name: string;
	export let description: string;
	//export let image: string;
	//export let link: string;
</script>

<div class="rounded bg-gray-100 p-3.5">
	<!--
	<div class="mb-4 rounded bg-white py-20 text-center shadow-inner">
		<Icon icon="image" classes="text-6xl text-gray-400" />
	</div>
	-->
	<p class="font-semibold">{name}</p>
	<!--
	<p>{description}</p>
	-->
</div>
