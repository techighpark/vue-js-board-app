<template>
  <h1>Home</h1>
  <div>Welcome to my first vue example file</div>
  <TheLayout />
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import TheLayout from '../components/layouts/TheLayout.vue';

export default defineComponent({
  name: 'home',
  components: { TheLayout },
});
</script>

<style></style>
