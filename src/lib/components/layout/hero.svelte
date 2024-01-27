<script lang="ts">
</script>

<div class="mb-8 bg-[url('/waves.jpg')] bg-cover bg-bottom">
	<div class="bg-sky-950 bg-opacity-50">
		<div class="container mx-auto px-3.5 py-12 text-white sm:px-6 lg:py-36">
			<slot name="content" />
		</div>
		<slot name="modal" />
	</div>
</div>
