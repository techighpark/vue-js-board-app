<template>
  <FancyButton>
    Click me
    <!-- slot content -->
  </FancyButton>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import FancyButton from './FancyButton.vue';
export default defineComponent({
  components: { FancyButton },
});
</script>
