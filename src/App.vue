<template>
  <div id="app">
    <Search />

    <!-- Panels -->
    <div class="flex">
      <LeftPanel />
      <MiddlePanel />
    </div>
  </div>
</template>

<script>
import Search from './components/Search.vue';
import LeftPanel from './components/LeftPanel.vue';
import MiddlePanel from './components/MiddlePanel.vue';

export default {
  name: 'App',
  components: {
    Search,
    LeftPanel,
    MiddlePanel,
  },
};
</script>

<style src="./assets/tailwind.css"></style>
