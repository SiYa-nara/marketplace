<script>
	import HoverCover from '$lib/components/hovercover.svelte';
</script>

<div class="hero">
	<div class="the-center">
		<h1>marketplace</h1>
		<a href="#">login or signup</a>
	</div>
	<div id="houseplant">
		<HoverCover src="/houseplant.png" alt="a nice, generic houseplant" coverColor="#628238" />
	</div>
	<div id="camera">
		<HoverCover src="/camera.png" alt="a vintage camera" coverColor="#6F481C" />
	</div>
	<div id="chucks">
		<HoverCover src="/chucks.png" alt="a pair of converse chucks" coverColor="#AF8955" />
	</div>
	<div id="iphone">
		<HoverCover src="/iphone.png" alt="an arm holding a purple iphone" coverColor="#8475B2" />
	</div>
	<div id="pumas">
		<HoverCover src="/pumas.png" alt="a pair of kids puma shoes" coverColor="#2A79B4" />
	</div>
	<div id="bus">
		<HoverCover src="/bus.png" alt="a vintage VW bus" coverColor="#E9BD39" />
	</div>
	<div id="bike">
		<HoverCover
			src="/bike.png"
			alt="a sports bike with a wooden crate with bottles inside on it's back"
			coverColor="#EF943F"
		/>
	</div>
</div>

<style>
	:global(body, html) {
		margin: 0;
		padding: 0;
		width: 100%;
		height: 100%;
		overflow: hidden;
	}

	.hero {
		display: flex;
		justify-content: center;
		align-items: center;
		width: 100vw;
		height: 100vh;
		overflow: none;
	}

	h1 {
		font-family: 'Jost';
		font-size: 4.125rem;
		margin-bottom: 4px;
	}

	a {
		text-decoration: none;
		background-color: #f0f0f0;
		color: #000;
		font-family: 'Jost';
		font-weight: 300;
		padding: 8px;
	}

	#houseplant {
		position: absolute;
		top: 180px;
		left: 50px;
	}

	#camera {
		position: absolute;
		bottom: 120px;
		right: 170px;
	}

	#chucks {
		position: absolute;
		bottom: 40px;
		left: 200px;
	}

	#iphone {
		position: absolute;
		top: 85px;
		right: 230px;
	}

	#pumas {
		position: absolute;
		top: 15px;
		right: 630px;
	}

	#bus {
		position: absolute;
		top: 15px;
		right: 5px;
	}

	#bike {
		position: absolute;
		bottom: 5px;
		right: 380px;
	}
</style>
