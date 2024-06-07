<script lang="ts">
	import '../app.css';
	import Sun from 'lucide-svelte/icons/sun';
	import Moon from 'lucide-svelte/icons/moon';
	import { useTheme } from '$lib/stores/useTheme.svelte';

	let theme = useTheme();

	$effect(() => {
		theme.darkMode;
		document.documentElement.classList.toggle('dark');
	});
</script>

<button onclick={theme.toggleDarkmode} class="absolute right-5 top-5">
	{#if theme.darkMode}
		<Sun />
	{:else}
		<Moon />
	{/if}
</button>

<header class="max-w-full bg-slate-600 py-3">
	<div class="container grid items-center lg:grid-cols-header">
		<img src="/pinata.svg" alt="Pinyata logo" class="mr-auto size-10" />
		<h1
			class="mr-auto hidden font-montserrat text-4xl font-semibold text-slate-900 lg:inline-block"
		>
			Pinyata Store
		</h1>
		<nav class="col-span-2 col-start-2 inline-block lg:col-start-3">
			<ul class="flex items-center justify-end gap-4">
				<li><a href="/products">Products</a></li>
				<li><a href="/about">About Us</a></li>
				<li><a href="/contact">Contact Us</a></li>
				<li><a href="/github.com">Github</a></li>
			</ul>
		</nav>
	</div>
</header>

<main class="container min-h-screen">sdghosgoag</main>

<slot />
