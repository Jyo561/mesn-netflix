<script>
	import ListItem from '../listitems/Listitem.svelte';
	import './list.css';
	let isMoved=false;
	export let slideNumber=0;
	let inputx;
	function handleClick(direction){
		isMoved=true;
		let distance=inputx.getBoundingClientRect().x-42.5
		if(direction === "left" && slideNumber > 0){
			slideNumber-=1;
			inputx.style.transform=`translateX(${230 + distance}px)`;
		}
		if(direction === "right" && slideNumber < 3){
			slideNumber+=1;
			inputx.style.transform=`translateX(${-230 + distance}px)`;
		}
	}
	
</script>

<main>
	<div class="list">
		<span class="listTitle">Continue to watch</span>
		<div class="wrapper">
			<i class="bi bi-caret-left-fill" on:click={handleClick('left')} style:display={ !isMoved ? "none" : "block" } ></i>
			<div class="container" bind:this={inputx} >
				<ListItem  />
				<ListItem  />
				<ListItem  />
                <ListItem  />
				<ListItem  />
				<ListItem  />
				<ListItem  />
				<ListItem  />
				<ListItem  />
				<ListItem  />
				<ListItem  />
			</div>
			<i class="bi bi-caret-right-fill" on:click={handleClick('right')} ></i>
		</div>
	</div>
</main>

<style>
	
</style>