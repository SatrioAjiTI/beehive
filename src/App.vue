<template>
  <Beranda />
</template>

<script>
import BerandaVue from "./components/Beranda.vue";
export default {
  name: "App",
  components: {
    Beranda: BerandaVue,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,500;0,900;1,900&display=swap");

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  font-family: "Bellota Text";
  font-style: normal;
}
</style>
