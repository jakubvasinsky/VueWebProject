<template>
  <div id="app">
    <header class="header">{{text1}}</header>
    <h2>{{text2}}</h2>
    <div class="text3">
      Our Artificial Intelligence powered tools use millions of project data points
      to ensure that your project is successful
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
  components: {},
  data() {
    return {
      text2: "Powered by Technology",
      text1: "Reliable, efficient delivery"
    };
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
