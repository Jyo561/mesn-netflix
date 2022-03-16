<script>
	import './listitem.css';
	let isHovered=false;
	let trailer='https://player.vimeo.com/external/371433846.sd.mp4?s=236da2f3c0fd273d2c6d9a064f3ae35579b2bbdf&profile_id=139&oauth2_token_id=57447761'
	//export let index;
</script>

<main>
	<div class="listitem" on:mouseover={isHovered=true} on:mouseout={isHovered=false} style:left={isHovered ? 240-30.5+'px' : '' }>
		<img src="https://occ-0-1723-92.1.nflxso.net/dnm/api/v6/X194eJsgWBDE2aQbaNdmCXGUP-Y/AAAABU7D36jL6KiLG1xI8Xg_cZK-hYQj1L8yRxbQuB0rcLCnAk8AhEK5EM83QI71bRHUm0qOYxonD88gaThgDaPu7NuUfRg.jpg?r=4ee" alt="">
		<section>
			
			<div class="itemInfo">
				<div class="icons">
					<i class="bi bi-play-fill" id="icon"></i>
					<i class="bi bi-info" id="icon"></i>
					<i class="bi bi-hand-thumbs-up" id="icon"></i>
					<i class="bi bi-hand-thumbs-down" id="icon"></i>
				</div>
				<div class="itemInfoTop">
					<span>1 hour 14 mins</span>
					<span class="limit">+16</span>
					<span>199</span>
				</div>
				<div class="desc">
					Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit voluptatem facilis placeat, 
				</div>
				<div class="genre">Action</div>
			</div>
		</section>
	</div>
</main>

<style>
	
</style>