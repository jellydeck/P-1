<script lang="ts">
	import Calculator from '$lib/components/Calculator.svelte';
	import TE from '$lib/components/TE.svelte';
</script>

<div class="relative">
	<Calculator class="pointer-none mx-auto w-full  sm:w-[65vw]" />

	<TE class="absolute top-2 w-(--step-9) max-sm:left-2 sm:right-0" />
</div>

<div class="bg-black py-20 text-center">
	<div class="mx-auto max-w-[65ch]">
		<h1 class="text-center text-(length:--step-10) font-light">P-I</h1>
		<p>tiny and mighty.</p>
		<p>basics in your pocket.</p>
	</div>
</div>

<div class="space-y-15 bg-gray px-5 py-30 text-center text-black">
	<div class="mx-auto max-w-[75ch]">
		<p>pocket friendly calculator stripped to basics</p>
		<p>built around your muscle memory</p>

		<!-- <p>designed to work <i>with</i> your muscle memory</p> -->
		<!-- <p>add, substract, multiply and divide numbers quickly.</p> -->
		<!-- <p>there is intentionaly one clear button that clears whole screen.</p> -->
	</div>

	<div class="mx-auto max-w-[75ch]">
		<p class="text-(length:--step-4)">
			P-I removes all the unnecessary functions and focuses on simple arithmetic operations.
		</p>
	</div>

	<div class="mx-auto max-w-[75ch]">
		<p>comes with finger rest so you can be rest assured.</p>
		<!-- <p>not useful for scientific calculations*</p> -->
	</div>
</div>
