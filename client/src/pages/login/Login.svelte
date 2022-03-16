<script>
	let email='';
	let password='';
	import './login.css';
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
		<form>
			<h1>Sign In</h1>
			<input type="email" placeholder="Email or Phone Number" bind:value={email}/>
			<input type="password" placeholder="Password" bind:value={password}/>
			<button class="loginButton">Sign In</button>
			<span>New to Netflix? <b>Sign up now</b></span>
			<small>
				This page is created by Google reCAPTCHA to ensure youre not a bot <b>Learn more</b>.
			</small>
		</form>
	</div>
 </div>	
</main>
<style>
	
</style>