<svelte:options tag="sv-counter" />

<script>
	let count = 0;
</script>

<p>{count}</p>
<button on:click={() => (count += 1)}>Click</button>

<style lang="scss">
	p {
		font-weight: 700;
	}
</style>