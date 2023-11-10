<script>
	import Header from './Header.svelte';
	import './styles.css';
  import TempMain from "$lib/images/temp-main.png"
</script>


<div class="background" >
<div class="app">
	<Header />

<img src={TempMain} />


	<!-- <Header />

	<main>
		<slot />
	</main>

	<footer>
		<p>visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to learn SvelteKit</p>
	</footer> -->
</div>
</div>
<style>

.background {
	background-color: black;
}
	.app {
		max-width: 735px;
		margin: auto;
		display: flex;
		flex-direction: column;
		height: 100dvh;
	}

	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		max-width: 64rem;
		margin: 0 auto;
		box-sizing: border-box;
	}

	footer {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		padding: 12px;
	}

	footer a {
		font-weight: bold;
	}

	@media (min-width: 480px) {
		footer {
			padding: 12px 0;
		}
	}
</style>
