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
	<div class="mx-auto max-w-[75ch] space-y-8">
		<p class="mx-auto w-fit rounded-md bg-orange px-2 text-white">limited edition</p>
		<p>
			GSLV-15 carrying NVS-02 navigation satellite, marked the 100<sup>th</sup> launch of ISRO and to
			celebrate this landmark, we're collaborating to create an exclusive calculator.
		</p>
	</div>

	<div class="mx-auto max-w-[75ch]"></div>

	<div class="md:mx-30">
		<CalculatorFront />
	</div>

	<div class="mx-auto max-w-[75ch]">
		<p>only 100 units</p>
	</div>

	<div>
		<a
			href="https://jaydip.me"
			class="text-(length:--step-2) text-blue"
			target="_blank"
			rel="noreferrer noopener">buy now</a
		>
	</div>

	<div class="mx-auto max-w-[75ch]">
		<p>a calculator with essential operations &amp; a clear screen key.</p>
		<p>enclosed in compact body you can slide easily into your pocket.</p>
		<p>comes with a coin battery that lasts months.</p>
	</div>

	<div class="mx-auto max-w-[75ch] space-y-4">
		<p>
			We were inspired by the relentless and bold attitude of the ISRO, we reflected it in the
			design with only one "All Clear" key.
		</p>
		<p>It pushes you to commit.</p>
	</div>
</div>

<Specs />

<div class=" bg-gray text-black text-center py-10">
    <div class="mx-auto max-w-[75ch]">
	<p>
		a concept site by
		<a class="text-(length:--step-1) text-blue" href="https://jaydip.me" target="_blank" rel="noreferrer noopener">jaydip sanghani</a>
	</p>
    </div>
</div>

<Footer />
