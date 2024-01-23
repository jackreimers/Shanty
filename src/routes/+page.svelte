<script>
	import Countdown from '$lib/components/countdown.svelte';
	import Button from '$lib/components/button.svelte';
	import Icon from '$lib/components/icon.svelte';
</script>

<div class="mx-auto mt-[-42px] w-1/2 rounded bg-white p-2 shadow-md">
	<div class="grid grid-cols-3 gap-2 text-center">
		<div class="flex items-center">
			<div class="mx-auto flex items-center gap-2 p-2">
				<Icon icon="calendar_month" weight={500} />
				<p class="font-semibold">1 January 1970</p>
			</div>
		</div>
		<div class="flex items-center border-x-2 border-gray-200">
			<div class="mx-auto flex items-center gap-2 p-2">
				<Icon icon="artist" weight={500} />
				<p class="font-semibold">10 Artists</p>
			</div>
		</div>
		<div class="flex items-center">
			<div class="mx-auto flex items-center gap-2 p-2">
				<Icon icon="question_mark" weight={500} />
				<p class="font-semibold">Something Else</p>
			</div>
		</div>
		<div class="col-span-3 mt-3">
			<Button classes="block bg-orange-100 p-3 font-bold">Get Tickets Now</Button>
		</div>
	</div>
</div>

<div class="flex flex-col gap-6">
	<!--
	<section class="mx-auto w-full text-center">
		<Button classes="inline-block w-full border border-gray-500 px-5 py-3 font-semibold">
			Get Tickets Now
			<Icon icon="open_in_new" />
		</Button>
	</section>
	<section class="rounded bg-gray-100 p-2.5">
		<h1 class="font-semibold">Welcome!</h1>
		<p>
			Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
			incididunt ut labore et dolore magna aliqua.
		</p>
	</section>

	<section class="rounded bg-gray-100 p-2.5">
		<div class="mb-2 flex items-center gap-2">
			<Icon icon="artist" weight={500} classes="rounded-full bg-gray-200 p-2" />
			<p class="font-semibold">Lineup</p>
		</div>
		<div class="">
			<p>
				Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
				incididunt ut labore et dolore magna aliqua.
			</p>
		</div>
	</section>

	<section>
		<div class="mb-2 flex items-center gap-2">
			<Icon icon="apparel" weight={500} classes="rounded-full bg-gray-200 p-2" />
			<p class="font-semibold">Merchandise</p>
		</div>
		<div class="rounded bg-gray-100 p-2.5">
			<p>
				Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
				incididunt ut labore et dolore magna aliqua.
			</p>
		</div>
	</section>

	<section>
		<div class="mb-2 flex items-center gap-2">
			<Icon icon="near_me" weight={500} classes="rounded-full bg-gray-200 p-2" />
			<p class="font-semibold">Venue</p>
		</div>
		<div class="rounded bg-gray-100 p-2.5">
			<p>
				Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
				incididunt ut labore et dolore magna aliqua.
			</p>
		</div>
	</section>

	<section>
		<div class="mb-2 flex items-center gap-2">
			<Icon icon="volunteer_activism" weight={500} classes="rounded-full bg-gray-200 p-2" />
			<p class="font-semibold">Volunteering</p>
		</div>
		<div class="rounded bg-gray-100 p-2.5">
			<p>
				Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
				incididunt ut labore et dolore magna aliqua.
			</p>
		</div>
	</section>

	<section>
		<div class="mb-2 flex items-center gap-2">
			<Icon icon="ad" weight={500} classes="rounded-full bg-gray-200 p-2" />
			<p class="font-semibold">Advertising</p>
		</div>
		<div class="rounded bg-gray-100 p-2.5">
			<p>
				Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
				incididunt ut labore et dolore magna aliqua.
			</p>
		</div>
	</section>

	<section>
		<div class="mb-2 flex items-center gap-2">
			<Icon icon="payments" weight={500} classes="rounded-full bg-gray-200 p-2" />
			<p class="font-semibold">Sponsors</p>
		</div>
		<div class="rounded bg-gray-100 p-2.5">
			<p>
				Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
				incididunt ut labore et dolore magna aliqua.
			</p>
		</div>
	</section>

	<section>
		<div class="mb-2 flex items-center gap-2">
			<Icon icon="help" weight={500} classes="rounded-full bg-gray-200 p-2" />
			<p class="font-semibold">FAQ</p>
		</div>
		<div class="rounded bg-gray-100 p-2.5">
			<p>
				Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
				incididunt ut labore et dolore magna aliqua.
			</p>
		</div>
	</section>
	-->
</div>
