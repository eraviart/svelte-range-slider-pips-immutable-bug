<script>
	import RangeSlider from "svelte-range-slider-pips";

	let range=[10]
</script>

<svelte:head>
	<title>Example of range slider working without immutable option</title>
</svelte:head>

<RangeSlider bind:values={range} />
