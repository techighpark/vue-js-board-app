<template>
  <!-- <ComponentAVue label="hello" v-bind:done="true" /> -->
  <Router />
  <router-view />
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import Router from '@components/Router.vue';

export default defineComponent({
  name: 'app',
  components: { Router },
});
</script>
