<script>
	import Nav from '$lib/components/nav.svelte';
</script>

<Nav />
<div class="slot">
	<slot />
</div>

<style>
	.slot {
		background-color: black;
		position: absolute;
		overflow-y: scroll;
		height: 100%;
	}
</style>
