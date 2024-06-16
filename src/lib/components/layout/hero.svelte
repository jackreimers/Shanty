<script lang="ts">
	import Icon from '$lib/components/icon.svelte';
	import Button from '$lib/components/button.svelte';
	import Container from '$lib/components/layout/container.svelte';
</script>

<div class="mb-8 bg-[url('/images/banner.png')] bg-cover bg-bottom">
	<Container classes="py-10 lg:py-32">
		<div class="inline-block rounded bg-gray-100 p-6">
			<slot name="content" />
		</div>
	</Container>
	<slot>
		<div class="bg-gradient-to-b from-transparent from-50% to-white to-50%">
			<Container>
				<div
					class="mx-auto mb-3 w-full max-w-[800px] rounded bg-[rgb(53,98,108)] p-2 text-white shadow-lg"
				>
					<div class="grid grid-rows-3 gap-2 md:grid-cols-2 md:grid-rows-1">
						<div class="flex items-center gap-2 p-2 md:mx-auto">
							<Icon icon="calendar_month" weight={500} />
							<p class="font-semibold">28th - 30th June 2024</p>
						</div>
						<div class="mx-auto w-full text-center">
							<Button
								href="https://events.humanitix.com/the-bunbury-sea-shanty-festival"
								target="_blank"
								classes="block rounded bg-sky-600 p-3 font-bold text-white shadow-[rgba(50,_50,_105,_0.15)_0px_2px_5px_0px,_rgba(0,_0,_0,_0.05)_0px_1px_1px_0px]"
							>
								Get Tickets
							</Button>
						</div>
					</div>
				</div>
			</Container>
		</div>
	</slot>
</div>
