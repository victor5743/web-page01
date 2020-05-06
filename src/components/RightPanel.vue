<template>
	<div class="w-1/4 border-l-2 border-gray-400 bg-white shadow-md">
		<div class="flex items-center justify-between p-4 mb-2">
			<div class="font-semibold text-lg">Notes</div>
			<button
				class="uppercase text-xs font-bold tracking-wide rounded border border-gray-800 px-4 py-2 hover:text-white hover:bg-gray-800"
			>
				+ New Note
			</button>
		</div>

		<div
			class="flex items-center text-sm font-semibold border-b border-gray-500 px-4 mb-4 justify-between"
		>
			<div class="border-b-4 border-primary pb-4">Notes Only</div>
			<div class="border-b-4 border-primary pb-4">Audits Only</div>
			<div class="border-b-4 border-primary pb-4">Everything</div>
		</div>

		<div class="flex px-4 mb-4">
			<div class="text-secondary mr-2">
				<svg
					class="fill-current"
					xmlns="http://www.w3.org/2000/svg"
					viewBox="0 0 24 24"
					width="24"
					height="24"
				>
					<path
						class="heroicon-ui"
						d="M6.3 12.3l10-10a1 1 0 0 1 1.4 0l4 4a1 1 0 0 1 0 1.4l-10 10a1 1 0 0 1-.7.3H7a1 1 0 0 1-1-1v-4a1 1 0 0 1 .3-.7zM8 16h2.59l9-9L17 4.41l-9 9V16zm10-2a1 1 0 0 1 2 0v6a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V6c0-1.1.9-2 2-2h6a1 1 0 0 1 0 2H4v14h14v-6z"
					/>
				</svg>
			</div>
			<div class="mb-2">
				<div class="text-sm leading-normal mb-2">
					The client called and said their fence fell over.
				</div>
				<div class="text-sm text-gray-600">April 15, 2020 9:36am</div>
			</div>
		</div>
		<div class="flex px-4 mb-4">
			<div class="text-secondary mr-2">
				<svg
					class="fill-current"
					xmlns="http://www.w3.org/2000/svg"
					viewBox="0 0 24 24"
					width="24"
					height="24"
				>
					<path
						class="heroicon-ui"
						d="M6.3 12.3l10-10a1 1 0 0 1 1.4 0l4 4a1 1 0 0 1 0 1.4l-10 10a1 1 0 0 1-.7.3H7a1 1 0 0 1-1-1v-4a1 1 0 0 1 .3-.7zM8 16h2.59l9-9L17 4.41l-9 9V16zm10-2a1 1 0 0 1 2 0v6a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V6c0-1.1.9-2 2-2h6a1 1 0 0 1 0 2H4v14h14v-6z"
					/>
				</svg>
			</div>
			<div class="mb-2">
				<div class="text-sm leading-normal mb-2">
					AOA 22228 was made the current AOA for PID GALDZOZ2R
				</div>
				<div class="text-sm text-gray-600">April 16, 2020 10:32am</div>
			</div>
		</div>
	</div>
</template>

<script>
export default {};
</script>
