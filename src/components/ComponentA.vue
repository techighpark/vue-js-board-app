<template>
  <div>
    <label :for="id">{{ label }}</label>
    <input type="checkbox" :id="id" :checked="isDone" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import uniqueId from 'lodash.uniqueid';

export default defineComponent({
  props: {
    label: { requied: true, type: String },
    done: { default: false, type: Boolean },
  },
  data() {
    return {
      isDone: this.done,
      id: uniqueId(`todo-${this.label}`),
    };
  },
});
</script>
