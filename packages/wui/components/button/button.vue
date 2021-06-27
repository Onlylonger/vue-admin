<template>
  <button>
    button-Exampleeeewww - {{count}}
  </button>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "WButton",
  data() {
    return {
      count: 1,
    };
  },
  mounted() {
    setInterval(() => {
      this.count++;
    }, 1000);
  },
});
</script>

<style lang="scss" scoped>
//
</style>