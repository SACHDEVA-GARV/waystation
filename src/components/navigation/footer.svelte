<script>
	let { stop } = $props();
</script>

<div class="bg-gray-300 p-3 text-black">
	<div class="flex items-center justify-between">
		<div class="flex items-center">
			<span class="ml-2 text-sm">Waystation by Open Transit Software Foundation</span>
		</div>
		<div class="text-sm">
			Stop No. {stop.code} - {stop.name}
		</div>
	</div>
</div>
