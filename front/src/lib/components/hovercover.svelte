<script>
	export let src;
	export let alt;
	export let coverColor;
</script>

<div class="hover" style="--cover-color: {coverColor}; --border-radius: 5%;">
	<img {src} {alt} />
</div>

<style>
	.hover {
		position: relative;
		display: inline-block;
        border-radius: var(--border-radius);
	}

	.hover::before {
		content: '';
		position: absolute;
		inset: 0;
        border-radius: var(--border-radius);
		background-color: var(--cover-color);
		z-index: 1;
		opacity: 1;
		transition: opacity 0.25s ease;
	}

	.hover:hover::before {
		opacity: 0;
	}

	img {
        display: block;
        position: relative;
		width: auto;
        border-radius: var(--border-radius);
	}
</style>
