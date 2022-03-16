<script >
import './home.css';
import Navbar from '../../components/Navbar.svelte'
import Featured from '../../components/featured/Featured.svelte';
import List from '../../components/list/List.svelte'
import List1 from '../../components/list/List.svelte'
import List2 from '../../components/list/List.svelte'
import List3 from '../../components/list/List.svelte'
</script>

<main>
	<div class="home">
		<Navbar />
		<Featured typ="movie" />
		<List />
		<List1 />
		<List2 />
		<List3 />
	</div>
</main>

<style >
	

</style>