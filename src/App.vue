<template>
  <div id="app">
    <calculator></calculator>
  </div>
</template>

<script>
import calculator from "./calculator.vue";
export default {
  name: "app",
  components: {
    calculator,
  },
};
</script>

<style>
body {
  background: #643843;
}
</style>
