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
      <div id="colored-text">
        <h3>Supervisor</h3>
      </div>Monitors activity to identify project roadblocks
      <div id="img1">
        <img src="assets/icon-supervisor.svg">
      </div>
    </div>

    <div id="box2">
      <div id="colored-text">
        <h3>Team Builder</h3>
      </div>Scans our talent network to
      create the optimal team for your project
      <div id="img2">
        <img src="assets/icon-team-builder.svg">
      </div>
    </div>

    <div id="box3">
      <div id="colored-text">
        <h3>Karma</h3>
      </div>Regularly evaluates our talent to ensure quality
      <div id="img3">
        <img src="assets/icon-karma.svg">
      </div>
    </div>

    <div id="box4">
      <div id="colored-text">
        <h3>Calculator</h3>
      </div>data from past projects
      to provide better delivery estimates
      <div id="img4">
        <img src="assets/icon-calculator.svg">
      </div>
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
  background-color: whitesmoke;
}
#header {
  font-size: 150%;
  margin-top: 30px;
}
#text3 {
  font-size: 80%;
  margin: 20px;
  color: gray;
}
#box1 {
  background-color: white;
  border-top-style: solid;
  border-color: hsl(180, 62%, 55%);
  background-origin: border-box;
  box-shadow: 5px;
  width: 350px;
  height: 200px;
  color: gray;
  margin-top: 50px;
}
#colored-text {
  color: rgb(0, 0, 0);
}
#box2 {
  background-color: white;
  border-top-style: solid;
  border-color: hsl(0, 78%, 62%);

  width: 350px;
  height: 200px;
  color: gray;
  margin-top: 50px;
}
#box3 {
  background-color: white;
  border-top-style: solid;
  border-color: hsl(34, 97%, 64%);

  width: 350px;
  height: 200px;
  color: gray;
  margin-top: 50px;
}
#box4 {
  background-color: white;
  border-top-style: solid;
  border-color: hsl(212, 86%, 64%);

  width: 350px;
  height: 200px;
  color: gray;
  margin-top: 50px;
}
</style>
