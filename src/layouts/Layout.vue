<template>
  <div id="layout">
    <Header />
    <router-view />
  </div>
</template>

<script>
import Header from "./Header.vue";

export default {
  name: "Layout",
  components: {
    Header,
  },
};
</script>

<style>
#layout {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
