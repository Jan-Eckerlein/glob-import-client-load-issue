<script>
	export let count = 0;
</script>

<section>
	<h1>Counter</h1>
	<p>Count: {count}</p>
	<button on:click={() => count++}>Increment</button>
	<button on:click={() => count--}>Decrement</button>
</section>

<style>
	section {
		border: 1px solid #ccc;
		padding: 0.5rem;
		margin: 0.5rem;
	}
</style>