<script lang="ts">
	import Icon from '$lib/components/icon.svelte';
	import Button from '$lib/components/button.svelte';

	let expanded: boolean = false;
</script>

<div class="w-full">
	<Button onClick={() => (expanded = !expanded)} classes="w-full text-left">
		<div
			class:rounded-b={!expanded}
			class="flex items-center rounded-t bg-gray-100 p-2.5 md:p-4"
		>
			<div class="flex-1 font-semibold leading-none">
				<slot name="title">
					<p>Title</p>
				</slot>
			</div>
			<div class:rotate-180={expanded}>
				<Icon icon="expand_more" classes="text-3xl" />
			</div>
		</div>
	</Button>
	<div class:h-0={!expanded} class:h-auto={expanded} class="overflow-hidden">
		<div class="rounded-b bg-gray-50 p-2.5 md:p-4">
			<slot name="content">
				<p>
					Fermentum dui faucibus in ornare quam viverra orci. Non diam phasellus
					vestibulum lorem sed risus ultricies tristique nulla.
				</p>
			</slot>
		</div>
	</div>
</div>
