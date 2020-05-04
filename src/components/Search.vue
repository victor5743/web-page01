<template>
	<div class="flex bg-primary">
		<!-- Logo -->
		<div class="px-4 py-2">
			<a href="#">
				<img class="h-12 w-12" src="../assets/logo.png" alt="Logo" srcset="" />
			</a>
		</div>
		<div class="w-full px-4 py-2 flex relative">
			<input
				class="ml-4 w-full px-12 py-2 rounded outline-0"
				type="text"
				placeholder="Search by Email, Property Address, PID, Phone Number or Contract Name"
			/>
			<div class="flex absolute px-8 py-3 text-gray-500">
				<svg
					class="h-6 w-6 fill-current"
					xmlns="http://www.w3.org/2000/svg"
					viewBox="0 0 20 20"
				>
					<path
						d="M12.9 14.32a8 8 0 1 1 1.41-1.41l5.35 5.33-1.42 1.42-5.33-5.34zM8 14A6 6 0 1 0 8 2a6 6 0 0 0 0 12z"
					/>
				</svg>
			</div>
		</div>
	</div>
</template>

<script>
export default {};
</script>
