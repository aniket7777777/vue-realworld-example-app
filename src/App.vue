<template>
  <div id="app">
    <v-select-wrapper v-model="selectedData" :options-data="['a', 'b']" />
  </div>
</template>

<script>
import RwvHeader from "@/components/TheHeader";
import RwvFooter from "@/components/TheFooter";
import VSelectWrapper from "./components/VSelectWrapper";

export default {
  name: "App",
  components: {
    RwvHeader,
    RwvFooter,
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
