<script lang="ts">
	export let onClick: Function | null = null;
	export let href: string = '';
	export let target: string = '';
	export let classes: string = '';
</script>

{#if onClick != null}
	<button class="transition-colors duration-500 {classes}" on:click={() => onClick?.call(null)}>
		<slot>
			<p>Button</p>
		</slot>
	</button>
{:else}
	<a {href} {target} class="transition-colors duration-500 {classes}">
		<slot>Button</slot>
	</a>
{/if}
