<script>
	import banner from '$lib/images/banner.jpeg';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>


<main>
		<picture>
			<source srcset={banner} type="image/webp" />
			<img width="720" height="320" src={banner} alt="Welcome" />
		</picture>
		<h1>COMING SOON!</h1>
	</main>

<style>
	:global(html), :global(body) {
		margin: 0;
		padding: 0;
	}
	main {
		height: 100vh;
		width: 100vw;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		background: black;
		color: white;
	}
</style>
