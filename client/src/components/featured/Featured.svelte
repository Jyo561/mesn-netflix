<script>
	import './featured.css';
	export let typ;
</script>

<main>
	<div class="featured">
		{#if typ != ''}
		<div class="category">
			{#if typ === 'movie'}
			<span>Movies</span>
			{:else}
			<span>Series</span>
			{/if}
			<select name="genre" id="genre">
			<option>Genre</option>
			<option value="adventure">Adventure</option>
            <option value="comedy">Comedy</option>
            <option value="crime">Crime</option>
            <option value="fantasy">Fantasy</option>
            <option value="historical">Historical</option>
            <option value="horror">Horror</option>
            <option value="romance">Romance</option>
            <option value="sci-fi">Sci-fi</option>
            <option value="thriller">Thriller</option>
            <option value="western">Western</option>
            <option value="animation">Animation</option>
            <option value="drama">Drama</option>
            <option value="documentary">Documentary</option>
			</select>
		</div>
		{/if}
		<img src="https://images.pexels.com/photos/6899260/pexels-photo-6899260.jpeg?auto=compress&cs=tinysrgb&dpr=2&w=500" alt="" />
		<div class="info">
			<img src="https://occ-0-1432-1433.1.nflxso.net/dnm/api/v6/LmEnxtiAuzezXBjYXPuDgfZ4zZQ/AAAABUZdeG1DrMstq-YKHZ-dA-cx2uQN_YbCYx7RABDk0y7F8ZK6nzgCz4bp5qJVgMizPbVpIvXrd4xMBQAuNe0xmuW2WjoeGMDn1cFO.webp?r=df1" alt="">
			<span class="desc">
				Lorem ipsum dolor sit amet consectetur adipisicing elit. Et non soluta dolorem saepe explicabo provident quo, unde praesentium, accusamus illo expedita qui repellendus nam amet dignissimos, voluptatum aperiam voluptate aliquam.
			</span>
			<div class="buttons">
				<button class="play">
					<i class="bi bi-play-fill"></i>
					<span>Play</span>
				</button>
				<button class="more">
					<i class="bi bi-info-circle-fill"></i>
					<span>Info</span>
				</button>
			</div>
		</div>
	</div>
</main>

<style>
	
</style>