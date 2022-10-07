<script>
	import logo from '$lib/images/logo.png';
	import wattpad from '$lib/images/wattpad.png';
</script>

<header class="items-center">
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
		background: #ff3131;
		color: black;
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
