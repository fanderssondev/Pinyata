<script>
	import Logo from '$lib/components/Logo.svelte';
	import '../app.css';
</script>

<header class="h-6 w-6">
	<Logo />
</header>

<slot />

<style>
	/* svg {
		width: 25px;
		height: 25px;
	} */
</style>
