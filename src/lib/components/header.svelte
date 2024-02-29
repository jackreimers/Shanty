<script lang="ts">
	import { goto } from '$app/navigation';
	import { page } from '$app/stores';

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

	function routeTo(path: string) {
		closeMenu();
		goto(path);
	}
</script>

<svelte:head>
	<title>Bunbury Sea Shanty Festival</title>
</svelte:head>

<header class="z-10 bg-amber-50 shadow-lg">
	<div class="container mx-auto px-4 sm:px-6 lg:flex">
		<div class="flex items-center md:flex-1">
			<a href="/" class="py-2.5">
				<img
					src="/images/logo.png"
					alt="Bunbury Sea Shanty Festival Logo"
					class="max-h-[60px] lg:max-h-[80px] xl:max-h-[100px]"
				/>
			</a>
			<div class="flex-1" />
			<Button onClick={openMenu} classes="rounded bg-sky-600 p-2 text-white xl:hidden">
				<Icon icon="menu" weight={400} />
			</Button>
		</div>
		<div class="mx-auto hidden gap-4 text-center xl:flex">
			<Button
				onClick={() => {
					routeTo('/');
				}}
				classes="flex items-center rounded-none px-4 font-medium hover:text-sky-600"
			>
				<span
					class:font-bold={$page.url.pathname === '/'}
					class:text-sky-600={$page.url.pathname === '/'}
				>
					Home
				</span>
			</Button>
			<Button
				onClick={() => {
					routeTo('/artists');
				}}
				classes="flex items-center rounded-none px-4 font-medium hover:text-sky-600"
			>
				<span
					class:font-bold={$page.url.pathname === '/artists'}
					class:text-sky-600={$page.url.pathname === '/artists'}
				>
					2024 Lineup
				</span>
			</Button>
			<Button
				onClick={() => {
					routeTo('/venues');
				}}
				classes="flex items-center rounded-none px-4 font-medium hover:text-sky-600"
			>
				<span
					class:font-bold={$page.url.pathname === '/venues'}
					class:text-sky-600={$page.url.pathname === '/venues'}
				>
					Venues
				</span>
			</Button>
			<Button
				onClick={() => {
					routeTo('/programs');
				}}
				classes="flex items-center rounded-none px-4 font-medium hover:text-sky-600"
			>
				<span
					class:font-bold={$page.url.pathname === '/programs'}
					class:text-sky-600={$page.url.pathname === '/programs'}
				>
					Programs
				</span>
			</Button>
			<Button
				onClick={() => {
					routeTo('/volunteer');
				}}
				classes="flex items-center rounded-none px-4 font-medium hover:text-sky-600"
			>
				<span
					class:font-bold={$page.url.pathname === '/volunteer'}
					class:text-sky-600={$page.url.pathname === '/volunteer'}
				>
					Volunteer
				</span>
			</Button>
			<Button
				onClick={() => {
					routeTo('/faq');
				}}
				classes="flex items-center rounded-none px-4 font-medium hover:text-sky-600"
			>
				<span
					class:font-bold={$page.url.pathname === '/faq'}
					class:text-sky-600={$page.url.pathname === '/faq'}
				>
					FAQ
				</span>
			</Button>
			<Button
				onClick={() => {
					routeTo('/contact');
				}}
				classes="flex items-center rounded-none px-4 font-medium hover:text-sky-600"
			>
				<span
					class:font-bold={$page.url.pathname === '/contact'}
					class:text-sky-600={$page.url.pathname === '/contact'}
				>
					Contact
				</span>
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
		>
			<div class="flex flex-col items-start gap-3 p-4 text-left text-2xl">
				<Button
					onClick={() => {
						routeTo('/');
					}}
					classes="font-medium hover:text-sky-600"
				>
					<span
						class:font-bold={$page.url.pathname === '/'}
						class:text-sky-600={$page.url.pathname === '/'}
					>
						Home
					</span>
				</Button>
				<Button
					onClick={() => {
						routeTo('/artists');
					}}
					classes="font-medium hover:text-sky-600"
				>
					<span
						class:font-bold={$page.url.pathname === '/artists'}
						class:text-sky-600={$page.url.pathname === '/artists'}
					>
						2024 Lineup
					</span>
				</Button>
				<Button
					onClick={() => {
						routeTo('/venues');
					}}
					classes="font-medium hover:text-sky-600"
				>
					<span
						class:font-bold={$page.url.pathname === '/venues'}
						class:text-sky-600={$page.url.pathname === '/venues'}
					>
						Venues
					</span>
				</Button>
				<Button
					onClick={() => {
						routeTo('/programs');
					}}
					classes="font-medium hover:text-sky-600"
				>
					<span
						class:font-bold={$page.url.pathname === '/programs'}
						class:text-sky-600={$page.url.pathname === '/programs'}
					>
						Programs
					</span>
				</Button>
				<Button
					onClick={() => {
						routeTo('/volunteer');
					}}
					classes="font-medium hover:text-sky-600"
				>
					<span
						class:font-bold={$page.url.pathname === '/volunteer'}
						class:text-sky-600={$page.url.pathname === '/volunteer'}
					>
						Volunteer
					</span>
				</Button>
				<Button
					onClick={() => {
						routeTo('/faq');
					}}
					classes="font-medium hover:text-sky-600"
				>
					<span
						class:font-bold={$page.url.pathname === '/faq'}
						class:text-sky-600={$page.url.pathname === '/faq'}
					>
						FAQ
					</span>
				</Button>
				<Button
					onClick={() => {
						routeTo('/contact');
					}}
					classes="font-medium hover:text-sky-600"
				>
					<span
						class:font-bold={$page.url.pathname === '/contact'}
						class:text-sky-600={$page.url.pathname === '/contact'}
					>
						Contact
					</span>
				</Button>
			</div>
		</div>
	</div>
</div>

<Blocker {open} onClick={closeMenu} />

<svelte:window on:scroll={() => onScroll()} />
