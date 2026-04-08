<script>
	let { children } = $props();
</script>

<svelte:head>
</svelte:head>

{@render children()}

<footer>
	<p>Ⓒ polimi 2026</p>
</footer>

<style>
    :global(p) {
        color: deeppink;
    }
</style>