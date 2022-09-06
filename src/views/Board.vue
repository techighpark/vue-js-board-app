<template>
  <div>Board</div>
  <BoardHeader />
  <BoardBody />
  <BoardFooter />
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import BoardFooter from '@components/BoardFooter.vue';
import BoardHeader from '@components/BoardHeader.vue';
import BoardBody from '@components/BoardBody.vue';

export default defineComponent({
  components: {
    BoardHeader,
    BoardBody,
    BoardFooter,
  },
});
</script>

<style></style>
