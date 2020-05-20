<template>
  <div id="app">
    <header id="header">
      {{text1}}
      <div id="bold-text">
        <b>{{text2}}</b>
      </div>
    </header>
    <div id="text3">Our Artificial Intelligence powered tools use millions of project data
      <div>
        points
        to ensure that your project is successful
      </div>
    </div>

    <div id="box1">
      <h3>Supervisor</h3>Monitors activity to identify project roadblocks
    </div>

    <div id="box2">
      <h3>Team Builder</h3>Scans our talent network to
      create the optimal team for your project
    </div>

    <div id="box3">
      <h3>Karma</h3>Regularly evaluates our talent to ensure quality
    </div>

    <div id="box4">
      <h3>Calculator</h3>Uses data from past projects
      to provide better delivery estimates
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
  margin-top: 30px;
}
#header {
  font-size: 150%;
}
#text3 {
  font-size: 80%;
  margin: 20px;
  color: gray;
}
#box1 {
  border: 5px, color black;
  width: 350px;
  height: 200px;
  color: gray;
}
</style>
