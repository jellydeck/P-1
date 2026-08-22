<script lang="ts">
	import Calculator from '$lib/components/Calculator.svelte';
	import CalculatorFront from '$lib/components/CalculatorFront.svelte';
	import Footer from '$lib/components/Footer.svelte';
	import TE from '$lib/components/TE.svelte';

	import rocket from '$lib/assets/rocket_launch_isro.jpg';
	import Specs from '$lib/components/Specs.svelte';
</script>

<div class="relative">
	<Calculator class="pointer-none mx-auto w-full  sm:w-[65vw]" />

	<TE class="absolute top-2 w-(--step-9) max-sm:left-2 sm:right-0" />
</div>

<div class="bg-black py-20 text-center">
	<div class="mx-auto max-w-[65ch] pb-20">
		<h1 class="mb-10 text-center text-(length:--step-10) font-light">P-I</h1>
		<p>tiny and mighty number crusher.</p>
	</div>
</div>

<div class="bg-black">
	<img src={rocket} alt="rocket launch of GSLV-F15 mission by ISRO" />
</div>

<div class="space-y-15 bg-gray px-5 py-30 text-center text-black">
	<div class="mx-auto max-w-[75ch]">
		<p class="mx-auto w-fit rounded-md bg-orange px-2 text-white">limited edition</p>
	</div>

	<div class="mx-auto max-w-[75ch]">
		<p>
			a calculator with only essential operations &amp; a clear screen button in compact body you
			can slide easily into your pocket. a coin battery that lasts months of use.
		</p>
	</div>

	<div class="md:mx-30">
		<CalculatorFront />
	</div>

	<div class="mx-auto max-w-[75ch]">
		<a href="https://jaydip.me" class="text-(length:--step-2) text-blue">buy now</a>
	</div>

	<div class="mx-auto max-w-[75ch] space-y-4">
		<p>designed with ISRO, only 100 editions</p>
		<p class="text-(length:--step-1)">
			these guys don't know when to turn back. so naturally, we were inspired with that attitude
			designed our calculator with one button to clear full screen. if it's wrong it ain't worth it.
		</p>
	</div>

	<!-- <div> -->
	<!-- <p>designed to work <i>with</i> your muscle memory</p> -->
	<!-- <p>add, subtract, multiply and divide numbers quickly.</p> -->
	<!-- <p>there is intentionaly one clear button that clears whole screen.</p> -->
	<!-- <p>comes with finger rest so you can be rest assured. not useful for scientific calculations*</p> -->
	<!-- </div> -->

	<!-- <div class="mx-auto max-w-[75ch]">
		<p>Space doesn't do undo. Neither do we.</p>
		<p>
		two distinct buttons: AC and = for your fingers to
		</p>
	</div> -->
</div>

<Specs />

<Footer />
