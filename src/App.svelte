<script>
	import Card from './components/Card.svelte';
</script>

<main>
	<nav>
		<a href="https://codeplus.duke.edu/" target="_blank">Code+</a>
		<a href="https://github.com/mpuglise04" target="_blank">More Code</a>
		<a href="https://svelte.dev/" target="_blank">Svelte</a>
	</nav>
	
	<h1>Welcome to the Museum!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
	<Card />

</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	nav {
		position: fixed;
  		width: 100%;
		display: flex;
		padding: 10px;
		justify-content: space-around; 
		z-index: 2;
		background-color: aliceblue;
		
	}

	a:hover {
		color: greenyellow;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	
	}
	
</style>