<script context="module" lang="ts">
	import skyscrapers from '$lib/images/skyscrapers.png';
</script>

<svelte:head>
	<title>Neo Diego</title>
</svelte:head>

<div
	style="background-image: url({skyscrapers})"
	class="gap-4 h-screen grid place-content-center text-center"
>
	<h1 class="text-4xl font-['AtariKids']">Neo Diego</h1>
	<h3 class="text-2xl font-['Japanese3017']">A cyberpunk story</h3>
	<p>A city to live, fight and die for.</p>
</div>
