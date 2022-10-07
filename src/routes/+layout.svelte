<script>
	import Header from 'C:/Users/E/Documents/cyberpunk/src/lib/components/Header.svelte';
	import Footer from '$lib/components/Footer.svelte';
	import '../app.css';
</script>

<body>
	<Header />
	<slot />
	<Footer />
</body>
