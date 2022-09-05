<template>
  <div>Board</div>
  <BoardHeader />
  <BoardFooter />
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import BoardFooter from '@components/BoardFooter.vue';
import BoardHeader from '@components/BoardHeader.vue';

export default defineComponent({
  components: {
    BoardFooter,
    BoardHeader,
  },
});
</script>

<style></style>
