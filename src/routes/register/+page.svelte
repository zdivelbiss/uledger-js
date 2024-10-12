<script>
</script>

<svelte:head>
	<title>µLedger: Login</title>
</svelte:head>

<form>
	<label for="display_name">What should we call you?</label>
	<input name="display_name" type="text" placeholder="your name..." />

	<label for="email_address">Your Email Address</label>
	<input name="email_address" type="text" placeholder="email address..." />

	<label for="password">Your Password</label>
	<input name="password" type="password" placeholder="password..." />

	<input type="submit" value="Login" />
</form>

<style lang="scss">
	form {
		display: flex;
		flex-flow: column nowrap;
	}
</style>
