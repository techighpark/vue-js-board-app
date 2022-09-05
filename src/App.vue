<template>
  <Home />
  <!-- <ComponentAVue label="hello" v-bind:done="true" /> -->
</template>

<script lang="ts">
import { defineComponent } from 'vue';
// import ComponentAVue from './components/ComponentA.vue';
import Home from './views/Home.vue';

export default defineComponent({
  name: 'app',
  components: {
    Home,
  },
});
</script>
