<script>
	import Image from 'svelte-image';
</script>

<style lang="scss">
	h1, p {
		text-align: center;
		margin: 0 auto;
	}

	h1 {
		font-size: 2.8em;
		text-transform: uppercase;
		font-weight: 700;
		margin: 0 0 0.5em 0;

		span {
			color: green;
		}
	}

	img {
		width: 100%;
		max-width: 400px;
		margin: 0 0 1em 0;
	}

	p {
		margin: 1em auto;
	}

	@media (min-width: 480px) {
		h1 {
			font-size: 4em;
		}
	}
</style>

<svelte:head>
	<title>Sapper project template</title>
</svelte:head>

<h1>Great <span>success!</span></h1>

<Image alt='Borat' src='great-success.png' />

<p><strong>Try editing this file (src/routes/index.svelte) to test live reloading.</strong></p>
