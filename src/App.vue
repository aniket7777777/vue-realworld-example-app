<template>
  <div id="app">
    <v-select-wrapper v-model="selectedData" :options-data="['a', 'b']" />
  </div>
</template>

<script>
import VSelectWrapper from "./components/VSelectWrapper";

export default {
  name: "App",
  components: {
    VSelectWrapper
  },
  data() {
    return {
      selectedData: null
    };
  }
};
</script>

<style></style>
