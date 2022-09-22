<div class="flex justify-center">
	<form on:submit|preventDefault class="p-4 mt-20 rounded-lg border m-auto">
		<h1 class="text-center text-xl">Sign In</h1>
		<div class="form-field">
			<label for="email">Email</label>
			<input type="email" id="email" class="form-input" placeholder="Email Address" name="email" />
		</div>
		<div class="form-field">
			<label for="password">Password</label>
			<input
				type="password"
				id="password"
				class="form-input"
				placeholder="Password"
				name="password"
			/>
		</div>
		<div class="my-5 w-full">
			<button type="submit" class="form-btn"> Submit </button>
		</div>
	</form>
</div>
