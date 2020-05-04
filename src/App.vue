<template>
	<div id="app">
		<Search />

		<!-- Panels -->
		<div class="flex">
			<PanelLeft />
		</div>
	</div>
</template>

<script>
import Search from './components/Search.vue';
import PanelLeft from './components/PanelLeft.vue';

export default {
	name: 'App',
	components: {
		Search,
		PanelLeft,
	},
};
</script>

<style src="./assets/tailwind.css"></style>
