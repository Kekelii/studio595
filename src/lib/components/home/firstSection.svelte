<script>
	import { onMount } from 'svelte';
	import Ukiyo from 'ukiyojs';

	onMount(() => {
		// const container = new Ukiyo('.bannerwriteup', {
		// 	speed: 2.1,
		// 	// scale: -0.5
		// 	wrapperClass: 'true'
		// });
	});
</script>

<section class="bannerwriteup pure-g">
	<div class="pure-u-5-5">
		<p>
			We create laughter and excitement out of designs, and strive hard to give humanity a
			fulfilling experience. Architecture of beauty and functionality is what we stand for.
		</p>
	</div>
	<div class="pure-u-5-5">
		<p>
			Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
			labore et dolore magna aliqua. Amet cursus sit amet dictum sit amet justo donec. Vitae sapien
			pellentesque habitant morbi tristique. Dictum sit amet justo donec enim diam vulputate.
			Ultricies integer quis auctor elit sed vulputate mi. Faucibus pulvinar elementum integer enim
			neque volutpat ac tincidunt vitae. Justo eget magna fermentum iaculis. Phasellus egestas
			tellus rutrum tellus pellentesque eu tincidunt tortor aliquam. Scelerisque varius morbi enim
			nunc faucibus a pellentesque. Enim blandit volutpat maecenas volutpat blandit aliquam etiam
			erat. Elementum tempus egestas sed sed risus pretium quam. Sed risus pretium quam vulputate.
			Libero nunc consequat interdum varius sit amet. Elit ut aliquam purus sit amet luctus
			venenatis lectus magna. Arcu dictum varius duis at consectetur. Ac felis donec et odio
			pellentesque diam volutpat. Enim lobortis scelerisque fermentum dui. Cursus vitae congue
			mauris rhoncus aenean vel elit scelerisque. Mattis aliquam faucibus purus in massa. Convallis
			convallis tellus id interdum velit laoreet id.
		</p>
	</div>
</section>

<style>
	.bannerwriteup {
		width: 100%;
		height: 60%;

		position: static;
		/* border: white solid 1px; */
		color: white;
		padding: 1px;
		margin: 0px;
		font-family: Montserrat;
		font-size: 12px;
		background-color: black;
	}
	.bannerwriteup p {
		text-align: left;
	}
	.bannerwriteup div {
		margin: 5px;
	}
	p {
		text-align: center;
	}
	section {
		overflow: scroll;
	}
</style>
