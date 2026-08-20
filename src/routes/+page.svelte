<script lang="ts">
	import Calculator from '$lib/components/Calculator.svelte';
	import CalculatorFront from '$lib/components/CalculatorFront.svelte';
	import Footer from '$lib/components/Footer.svelte';
	import TE from '$lib/components/TE.svelte';
</script>

<div class="relative">
	<Calculator class="pointer-none mx-auto w-full  sm:w-[65vw]" />

	<TE class="absolute top-2 w-(--step-9) max-sm:left-2 sm:right-0" />
</div>

<div class="bg-black py-20 text-center">
	<div class="mx-auto max-w-[65ch] pb-20">
		<h1 class="mb-10 text-center text-(length:--step-10) font-light">P-I</h1>
		<p>tiny and mighty.</p>
		<p>basics in your pocket.</p>
	</div>
</div>

<div class="space-y-15 bg-gray px-5 py-30 text-center text-black">
	<div class="mx-auto max-w-[75ch]">
		<p class="text-pretty">pocket friendly calculator to basics.</p>
	</div>

	<div class="mx-30">
		<CalculatorFront />
	</div>

	<div class="mx-auto max-w-[75ch]">
		<p class="text-(length:--step-4)">
			strip out all the unnecessary functions and focus on primitive arithmetic operations.
		</p>
	</div>

	<div class="mx-auto max-w-[75ch]">
		<p>designed in collaboration with ISRO</p>
	</div>

	<!-- <div> -->
	<!-- <p>designed to work <i>with</i> your muscle memory</p> -->
	<!-- <p>add, substract, multiply and divide numbers quickly.</p> -->
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

<Footer />
