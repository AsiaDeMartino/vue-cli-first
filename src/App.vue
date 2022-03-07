<template>
  <div id="app">
    <Title />
    <NuovoComponente />
  
  </div>
</template>

<script>
import NuovoComponente from "./components/NuovoComponente.vue";
import Title from "./components/Title.vue";

export default {
  name: "App",
  components: {
    NuovoComponente,
    Title,
  },
  
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
