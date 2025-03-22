<script>
	import HoverCover from '$lib/components/hovercover.svelte';
</script>

<div class="hero">
	<div class="the-center">
		<h1>marketplace</h1>
	</div>
	<div id="houseplant">
		<HoverCover src="/houseplant.png" alt="a nice, generic houseplant" coverColor="#628238" />
	</div>
</div>

<style>
	.hero {
		display: flex;
		justify-content: center;
		align-items: center;
		width: 100vw;
		height: 100vh;
	}

	h1 {
		font-family: 'Jost';
        font-size: 4.125rem;
	}

	#houseplant {
		position: absolute;
		top: 80px;
		left: 120px;
	}
</style>
