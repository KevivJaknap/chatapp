<script>
	import '../app.css';
	let username = '';
	let password = '';
</script>

<div class="">
	<div class="flex flex-col items-center justify-center">
		<div class="my-2 mx-3 w-1/2 border-2 border-black ">
			<div class="mx-2">
				<div class="">
					<label for="username">Username</label>
					<div class="border-2 border-black">
						<input type="text" id="username" bind:value={username} />
					</div>
				</div>
				<div class="mb-2">
					<label for="password">Password</label>
					<div class="border-2 border-black">
						<input type="password" id="password" bind:value={password} />
					</div>
				</div>
			</div>
			<div class="mb-2 flex justify-center">
				<button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
					Login
				</button>
			</div>
		</div>
	</div>
</div>
