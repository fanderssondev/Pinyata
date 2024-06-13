<script lang="ts">
	import Card from '$lib/components/Card.svelte';
	import SideInfo from '$lib/components/SideInfo.svelte';
	import Button from '$lib/components/ui/button/button.svelte';
</script>

<div class="mt-8 grid grid-cols-1 gap-4 lg:grid-cols-3">
	<section class="col-span-2">
		<div class="mb-8 grid grid-cols-1 gap-4 md:grid-cols-2">
			<img src="pinyata_ph.avif" alt="placeholder of a pinata" class="rounded-lg" />
			<img src="pinyata_ph.avif" alt="placeholder of a pinata" class="rounded-lg" />
		</div>

		<h1 class="mb-8 text-2xl">Colorful Pinata</h1>
		<p>
			Brighten up any celebration with our vibrant, handcrafted pinata, designed to bring fun and
			excitement to parties of all ages. Made from sturdy materials, it holds plenty of treats and
			goodies, ensuring a memorable surprise when it's finally broken open. Perfect for birthdays,
			holidays, and festive gatherings.
		</p>
	</section>

	<!-- <div class="rounded-lg bg-slate-100 dark:bg-slate-800">
		<div>€49.99</div>
		<Button>Add to cart</Button>
	</div> -->

	<SideInfo />
</div>
