<style>
	.cutoff-text {
		--max-lines: 4;
		--line-height: 1.5;

		height: calc(var(--max-lines) * 1em * var(--line-height));
		line-height: var(--line-height);
		position: relative;
		overflow: hidden;
	}

	.cutoff-text::before {
		content: '';
		position: absolute;
		height: calc(2em * var(--line-height));
		width: 100%;
		bottom: 0;
		pointer-events: none;
		background: linear-gradient(to bottom, transparent, rgb(184, 213, 209));
	}
</style>

<script lang="ts">
	export let name: string;
	export let description: string | null = null;
	export let imageUrl: string | null = null;
</script>

<div class="rounded bg-[rgb(184,213,209)] p-3.5">
	{#if imageUrl}
		<img src={imageUrl} alt={name} class="mb-3.5 w-full rounded" />
	{/if}
	<p class="text-xl font-semibold">{name}</p>
	{#if description}
		<div class="cutoff-text mt-2.5">
			<p>{description}</p>
		</div>
	{/if}
</div>
