<template>
  <div id="main">
    <h1 id="heading">{{ heading }}</h1>
  </div>
</template>

<script>
export default {
  name: "MainPage",
  data() {
    return {
      heading: "BeeStats",
    };
  },
};
</script>

<style>
#main {
  padding: 2rem;
  background-image: url("https://i.pinimg.com/originals/76/3e/7d/763e7d18853565ba7739b40f850b1e71.jpg");
}

#heading {
  font-family: RobotoMono, sans-serif;
  color: antiquewhite;
}
</style>
