<script lang="ts">
	import Icon from '$lib/components/icon.svelte';
	import Button from '$lib/components/button.svelte';
	import Container from '$lib/components/layout/container.svelte';
</script>

<div class="mb-8 bg-[url('/images/waves.jpg')] bg-cover bg-bottom">
	<div class="bg-sky-950 bg-opacity-50">
		<div class="container mx-auto px-3.5 py-12 text-white sm:px-6 lg:py-36">
			<slot name="content" />
		</div>
		<slot>
			<div class="bg-gradient-to-b from-transparent from-50% to-white to-50%">
				<Container>
					<div class="mx-auto mb-3 w-full max-w-[800px] rounded bg-white p-2 shadow-lg">
						<div class="grid grid-rows-3 gap-2 md:grid-cols-4 md:grid-rows-1">
							<div class="flex items-center gap-2 p-2 md:mx-auto">
								<Icon icon="calendar_month" weight={500} />
								<p class="font-semibold">21 August 2024</p>
							</div>
							<div class="md:flex md:border-x-2 md:border-slate-200">
								<div class="flex items-center gap-2 p-2 md:mx-auto">
									<Icon icon="artist" weight={500} />
									<p class="font-semibold">100 Artists</p>
								</div>
							</div>
							<div class="flex items-center gap-2 p-2 md:mx-auto">
								<Icon icon="family_restroom" weight={500} />
								<p class="font-semibold">Family Friendly</p>
							</div>
							<div class="mx-auto w-full text-center">
								<Button
									classes="block rounded bg-sky-600 p-3 font-bold text-white shadow-[rgba(50,_50,_105,_0.15)_0px_2px_5px_0px,_rgba(0,_0,_0,_0.05)_0px_1px_1px_0px]"
								>
									Get Tickets Now
								</Button>
							</div>
						</div>
					</div>
				</Container>
			</div>
		</slot>
	</div>
</div>
