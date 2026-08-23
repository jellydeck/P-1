<script>
	import CoinCell from '$lib/components/CoinCell.svelte';
	import Groove from './Groove.svelte';
	import Numbers from './Numbers.svelte';
	import UniqueKeys from './UniqueKeys.svelte';
</script>

<div class=" bg-gray text-black">
	<div class="grid grid-cols-2 md:grid-cols-[1fr_2fr_2fr] border border-light-gray gap-px bg-light-gray *:bg-gray *:p-4">
	<p class="text-(length:--step-2) bg-gray pl-2 col-span-2 md:col-span-1 md:col-start-1 md:row-start-1 md:row-span-4">Specification</p>
		<div class="flex items-center justify-center"><Numbers/> <Numbers start={1}/></div>
		<p class="flex items-center">seven-segment display for crisp numbers</p>
		<div class="flex items-center justify-center"><CoinCell class="w-50"/></div>
		<p class="flex items-center">coin cell battery that lasts months</p>
		<div class="flex items-center justify-center"><UniqueKeys class="w-45"/></div>
		<p class="flex items-center">distinct key shapes so your fingers can find the right key</p>
		<div class="flex items-center justify-center"><Groove class="w-45"/></div>
		<p class="flex items-center">machine-drilled grooves to rest your fingers, allowing you to refocus.</p>
	</div>
</div>
