<script>
	//import Home from './pages/home/Home.svelte'
	//import Watch from './pages/watch/Watch.svelte'
	import Register from './pages/register/Register.svelte'
	//import Login from './pages/login/Login.svelte'
	import './app.css';
</script>

<main>
	<div class="home">
		<Register />
	</div>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>