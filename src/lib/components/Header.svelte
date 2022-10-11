<script>
	import logo from '$lib/images/logo.png';
	import wattpad from '$lib/images/wattpadOrange.png';

	let showMenu = false;

	function toggleNavbar() {
		showMenu = !showMenu;
	}
</script>

<header class="text-white font-['pixeloidSans']">
	<div>
		<nav class="container px-6 py-8 mx-auto md:flex md:justify-between md:items-center">
			<div class="flex items-center justify-between">
				<a href="/"><img src={logo} alt="logo" class="h-14 " /></a>
				<!-- Mobile menu button -->
				<div on:click={toggleNavbar} class="flex md:hidden">
					<button
						type="button"
						class="text-white hover:text-gray-400 focus:outline-none focus:text-gray-400"
					>
						<svg
							xmlns="http://www.w3.org/2000/svg"
							fill="none"
							viewBox="0 0 24 24"
							stroke-width="1.5"
							stroke="currentColor"
							class="w-6 h-6"
						>
							<path
								stroke-linecap="round"
								stroke-linejoin="round"
								d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5"
							/>
						</svg>
					</button>
				</div>
			</div>

			<!-- Mobile Menu open: "block", Menu closed: "hidden" -->
			<div
				class="flex-col mt-8 space-y-4 md:flex md:space-y-0 md:flex-row md:items-center md:space-x-10 md:mt-0 {showMenu
					? 'flex'
					: 'hidden'}"
			>
				<a
					class="text-gray-800 hover:text-blue-400"
					href="https://www.wattpad.com/1276706698-neo-diego-synopsis"
					><img src={wattpad} alt="wattpadIcon" class="h-4" /></a
				>
				<a class="text-white hover:text-blue-400" href="/novel">Discover more</a>
			</div>
		</nav>
	</div>
</header>
