<template>
	<div class="block sm:flex bg-primary">
		<!-- Logo -->
		<div class="mx-auto flex ml-4 py-2 items-center">
			<div class="mx-auto flex items-center">
				<a href="#">
					<img class="w-16 h-16 sm:h-12" src="../assets/logo.png" alt="Logo" srcset="" />
				</a>
				<span class="text-lg font-semibold">Website</span>
			</div>
		</div>
		<div class="w-full pr-4 py-2 flex relative">
			<input
				class="ml-4 w-full px-12 py-2 rounded outline-0 border border-transparent focus:outline-none focus:border-secondary"
				type="text"
				placeholder="Search"
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
