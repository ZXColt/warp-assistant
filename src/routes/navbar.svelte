<script>
	import { each } from 'svelte/internal';

	const items = ['overview', 'test'];
</script>

<div>
	{#each items as item}
		<a href="/{item}">{item}</a>
	{/each}
</div>

<!-- markup -->
<style>
</style>
