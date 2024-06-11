<script lang="ts">
	export let name: string;
	export let description: string | null = null;
	export let imageUrl: string | null = null;
</script>

<div class="rounded bg-gray-100 p-3.5">
	{#if imageUrl}
		<img src={imageUrl} alt={name} class="mb-3.5 w-full rounded" />
	{/if}
	<p class="text-xl font-semibold">{name}</p>
	{#if description}
		<p class="mt-2.5">{description}</p>
	{/if}
</div>
