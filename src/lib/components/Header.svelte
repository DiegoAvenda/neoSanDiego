<script>
	import logo from '$lib/images/logo.png';
	import wattpad from '$lib/images/wattpad.png';
</script>

<header class="text-white font-['pixeloidSans'] items-center bg-zinc-800">
	<a href="/"><img src={logo} alt="logo" class="h-14 " /></a>

	<nav>
		<ul>
			<li>
				<a href="https://www.wattpad.com/user/Davendanoh"><img src={wattpad} alt="wattpadIcon" /></a
				>
			</li>
			<li>
				<a href="/novel">Novel</a>
			</li>
			<li>
				<a href="/about">About</a>
			</li>
			<li>
				<a href="/contact">Contact</a>
			</li>
		</ul>
	</nav>
</header>

<style>
	header {
		padding: 1rem;
		display: flex;
		flex-wrap: wrap;
		justify-content: space-between;
	}

	ul {
		margin: 0;
		list-style-type: none;
		display: flex;
		gap: 1rem;
	}

	a {
		text-decoration: none;
		color: inherit;
	}
</style>
