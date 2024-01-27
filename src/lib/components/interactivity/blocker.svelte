<style>
	button.visible {
		transition: opacity 0.5s linear;
	}

	button.invisible {
		transition:
			visibility 0s 0.5s,
			opacity 0.5s linear;
	}
</style>

<script lang="ts">
	export let open: boolean = false;
	export let onClick: Function | null = null;

	function handleClick() {
		onClick?.call(null);
		open = false;
	}
</script>

<button
	class:invisible={!open}
	class:visible={open}
	class:opacity-0={!open}
	class:opacity-100={open}
	class="fixed left-0 top-0 z-10 h-full w-full bg-black bg-opacity-50"
	on:click={handleClick}
/>
