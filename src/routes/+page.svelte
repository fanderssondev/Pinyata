<script lang="ts">
	import Card from '$lib/components/Card.svelte';
</script>

<section class="mt-8 grid grid-cols-1 gap-4 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4">
	{#each { length: 16 } as card}
		<Card />
	{/each}
</section>
