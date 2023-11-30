<script>
	import Header from '$lib/components/home/header.svelte';
	import FirstSection from '$lib/components/home/firstSection.svelte';
	import SecondSection from '$lib/components/home/secondSection.svelte';
	import ThirdSection from '$lib/components/home/thirdSection.svelte';
	import FourthSection from '$lib/components/home/fourthSection.svelte';
	import FifthSection from '$lib/components/home/fifthSection.svelte';
	import SixthSection from '$lib/components/home/sixthSection.svelte';
	import SeventhSection from '$lib/components/home/seventhSection.svelte';
	import EightSection from '$lib/components/home/eightSection.svelte';
	import NinethSection from '$lib/components/home/ninethSection.svelte';
</script>

<!-- banner img -->
<Header />
<FirstSection />
<SecondSection />
<ThirdSection />
<FourthSection />
<section class="secondsection bannerwriteup"></section>
<FifthSection />
<SixthSection />
<SeventhSection />
<EightSection />
<NinethSection />

<style>
	.bannerwriteup {
		width: 99%;
		height: 40%;
		position: relative;
		/* border: white solid 1px; */
		color: white;
		padding: 1px;
		margin: 0px;
		font-family: Montserrat;
		font-size: 12px;
	}
</style>
