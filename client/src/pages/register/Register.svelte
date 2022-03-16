<script>
	import './register.css'
	let email='';
	let password='';
	let statey='';

	function changeState(){
		statey=true;
	}
</script>
<main>
	 <div class="register">
	<div class="top">
		<div class="wrapper">
			<img class="logo" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/08/Netflix_2015_logo.svg/2560px-Netflix_2015_logo.svg.png" alt="" />
			<button class="loginButton">Sign In</button>
		</div>
	</div>
	<div class="container">
		<h1>Unlimited movies, TV shows, and more.</h1>
		<h2>Watch anywhere. Cancel anytime.</h2>
		<p>
			Ready to watch? Enter your email to create or restart your membership.
		</p>
		{#if !statey}
		<section >
			<div class="input">
			<input type="email" placeholder="email address" bind:value={email} />
			<button class="registerButton" on:click={changeState}>Get Started</button>
		</div>
		</section>
		{:else}
		<section>
			<div class="input">
			<input type="password" placeholder="password" bind:value={password} />
			<button class="registerButton"  >Get Started</button>
			</div>
		</section>
		{/if}
	</div>
 </div>	
</main>
<style>
	
</style>