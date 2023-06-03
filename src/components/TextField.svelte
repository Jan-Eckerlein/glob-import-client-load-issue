<script>
	export let value = '';
</script>

<section>
	<h1>TextField</h1>
	<input type="text" bind:value />
	<p>Value: {value}</p>
</section>

<style>
	section {
		border: 1px solid #ccc;
		padding: 0.5rem;
		margin: 0.5rem;
	}
</style>