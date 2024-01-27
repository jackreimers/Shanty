<script lang="ts">
	import Blocker from '$lib/components/interactivity/blocker.svelte';

	import Icon from '$lib/components/icon.svelte';
	import Button from '$lib/components/button.svelte';

	let open: boolean = false;

	let scrollTop: number = 0;
	let scrollLeft: number = 0;

	function onScroll() {
		//Lock the window scroll location if the menu is open
		if (open) window.scrollTo(scrollLeft, scrollTop);
	}

	function openMenu() {
		open = true;

		//Store the window scroll location
		scrollTop = window.scrollY || window.document.documentElement.scrollTop;
		scrollLeft = window.scrollX || window.document.documentElement.scrollLeft;
	}

	function closeMenu() {
		open = false;
	}
</script>

<svelte:head>
	<title>Bunbury Sea Shanty Festival</title>
</svelte:head>

<header class="z-10">
	<div class="container mx-auto px-4 sm:px-6 lg:flex">
		<div class="flex items-center md:flex-1">
			<h1 class="flex-1 py-6 font-semibold leading-none lg:text-2xl">
				Bunbury Sea Shanty Festival
			</h1>
			<Button onClick={openMenu} classes="bg-slate-700 p-2 text-white lg:hidden">
				<Icon icon="menu" weight={400} />
			</Button>
		</div>
		<div class="mx-auto hidden gap-4 text-center lg:flex">
			<Button classes="flex items-center px-4 pt-[4px] font-bold text-sky-700"
				>Overview</Button
			>
			<Button
				href="/artists"
				classes="flex items-center rounded-none px-4 font-medium hover:border-stone-600"
			>
				Lineup
			</Button>
			<Button
				classes="flex items-center rounded-none px-4 font-medium hover:border-stone-600"
			>
				FAQ
			</Button>
		</div>
	</div>
</header>

<div
	class:w-0={!open}
	class:w-[320px]={open}
	class:lg:w-[500px]={open}
	class="fixed right-0 top-0 z-20 h-full overflow-hidden bg-white transition-all duration-500"
>
	<div class="w-[320px] lg:w-[500px]">
		<div
			class:ml-0={open}
			class:ml-4={!open}
			class="transition-spacing p-4 delay-100 duration-700 lg:px-12 lg:py-8"
		></div>
	</div>
</div>

<Blocker {open} onClick={closeMenu} />

<svelte:window on:scroll={() => onScroll()} />
