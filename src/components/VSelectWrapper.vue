<template>
  <v-select :options="optionsData" :value="value" @input="inputChanged" />
</template>

<script>
import vSelect from "vue-select";

export default {
  name: "VSelectWrapper",
  components: {
    vSelect
  },
  props: {
    optionsData: { type: Array },
    value: {}
  },
  methods: {
    inputChanged(val) {
      this.$emit("input", val);
    }
  }
};
</script>

<style scoped />
