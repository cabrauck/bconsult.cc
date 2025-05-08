<!-- src/routes/+layout.svelte -->
<script>
	import '../app.css';
	export let data;
</script>

<nav class="bg-blue text-white p-4">
	<ul class="flex gap-4">
		<li><a href="/" class="hover:underline">Home</a></li>
		<li><a href="/about" class="hover:underline">Über mich</a></li>
		<li><a href="/contact" class="hover:underline">Kontakt</a></li>
		<li><a href="/impressum" class="hover:underline">Impressum</a></li>
		<li><a href="/privacy" class="hover:underline">Datenschutz</a></li>
	</ul>
</nav>

<main class="p-4 bg-blue-50">
	<slot />
</main>
