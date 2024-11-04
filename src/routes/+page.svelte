<script>
	import Regular from "$lib/popovers/Regular.svelte";
	import Timed from "$lib/popovers/Timed.svelte";
</script>
<div class="container mx-auto flex h-svh items-center justify-center">
	<span>
        <Regular />
        <Timed />
		<button class="btn preset-filled-primary-500">Open multiline toast</button>
		<button class="btn preset-filled-primary-500">Open animated toast</button>
	</span>
</div>
