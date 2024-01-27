<script lang="ts">
	export let bottomBuffer = false;
</script>

<div class="mb-8 bg-[url('/waves.jpg')] bg-cover bg-bottom shadow-inner">
	<div class="bg-sky-950 bg-opacity-50">
		<div
			class="container mx-auto px-3.5 pt-12 text-white sm:px-6 lg:py-36"
			class:pb-20={bottomBuffer}
			class:pb-12={!bottomBuffer}
		>
			<slot />
		</div>
	</div>
</div>
