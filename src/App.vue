<template>
  <div id="app">
    <img id="logo" alt="App logo" src="./assets/logo.png" />
    <WelcomeMK msg="Explore status of coffee machines in the office!" />
  </div>
</template>

<script>
import WelcomeMK from "./components/Welcome.vue";

export default {
  name: "App",
  components: {
    WelcomeMK,
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

#logo {
  width: 150px;
}
</style>
