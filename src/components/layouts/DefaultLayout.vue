<template>
  <div>
    <board-header />
    <slot />
    <board-footer />
  </div>
</template>

<script lang="ts">
import BoardHeader from '@components/BoardHeader.vue';
import BoardFooter from '@components/BoardFooter.vue';
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'DefaultLayout',
  components: {
    BoardHeader,
    BoardFooter,
  },
});
</script>
