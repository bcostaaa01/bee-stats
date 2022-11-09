<template>
  <div id="app">
    <NavBar />
    <MainPage />
  </div>
</template>

<script>
import NavBar from './components/NavBar/NavBar.vue';
import MainPage from './components/Pages/MainPage.vue';

export default {
  name: "App",
  components: {
    NavBar,
    MainPage
  },
  data() {
    return {
      heading: "BeeStats",
    };
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
