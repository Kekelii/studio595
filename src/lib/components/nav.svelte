<script>
	import { onMount } from 'svelte';

	onMount(() => {
		ScrollReveal().reveal('.links');
	});
</script>

<div class="pure-menu pure-menu-horizontal nav-bar">
	<!-- logo -->
	<a class="pure-menu-heading logo" href="/">
		<img src="/logo/studio logo001.png" alt="log" />
	</a>
	<!-- menu -->
	<ul class="links">
		<li><a href="/" class="pure-menu-link">HOME</a></li>
		<li><a href="/villas" class="pure-menu-link">Villas</a></li>
		<li><a href="/towers" class="pure-menu-link">Towers</a></li>
		<li><a href="/masterplan" class="pure-menu-link">Masterplan</a></li>
		<li><a href="/about" class="pure-menu-link">About Us</a></li>
		<li><a href="/contact" class="pure-menu-link">contact</a></li>
	</ul>
</div>

<style>
	.nav-bar {
		height: 50px;
		display: flex;
		position: absolute;
		z-index: 1;
	}
	.logo {
		/* border: red solid 1px; */
		height: 100%;
		padding: 0.5px;
	}
	.logo img {
		height: 48px;
	}

	.links {
		list-style-type: none;
		color: #666666;
		opacity: 0.9;
		display: flex;
		font-size: 8px;
		flex-wrap: wrap;
		justify-content: space-evenly;
		padding: 0;
	}
	.links a {
		color: black;
		text-transform: uppercase;
	}
</style>
