<script>
	import '../app.css';
</script>

<header class="max-w-full bg-slate-600 py-3">
	<div class="lg:grid-cols-header container grid items-center">
		<img src="/pinata.svg" alt="Pinyata logo" class="mr-auto size-10" />
		<h1
			class="font-montserrat mr-auto hidden text-4xl font-semibold text-slate-900 lg:inline-block"
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

<main class="container min-h-screen">gjhg</main>

<slot />
