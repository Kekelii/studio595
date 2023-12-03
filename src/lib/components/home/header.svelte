<script>
	import { onMount } from 'svelte';
	import Ukiyo from 'ukiyojs';

	onMount(() => {
		const bannerimage = new Ukiyo('#banner', { scale: 1.1 });
	});
</script>

<picture>
	<img id="banner" src="/home/banner/sm.png" loading="lazy" alt="banner" />
</picture>

<style>
	picture {
		height: 180px;
	}
	img {
		width: 100%;
	}
</style>
