<script lang="ts">
	import Icon from '$lib/components/icon.svelte';

	export let title: string;
	export let icon: string | null = null;
	export let classes: string = '';
</script>

<div class="mb-6 flex items-center gap-3 {classes}">
	{#if icon}
		<div class="rounded-full bg-[rgb(236,214,183)] p-3">
			<Icon {icon} />
		</div>
	{/if}
	<h2 class="header text-4xl leading-none">
		{title}
	</h2>
</div>
