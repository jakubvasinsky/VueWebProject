<template>
  <div id="app">
    <link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">
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
      </div>Uses data from past projects
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
  height: 1000px;
  width: 1340px;
  font-family: "Poppins", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: whitesmoke;
}
#header {
  font-size: 150%;
  /* font-weight: 600;*/

  padding: 30px;
}
#text3 {
  /* font-size: 80%;*/
  font-weight: 200;
  margin: 10px;
  color: gray;
}
#box1 {
  background-color: white;
  border-top-style: solid;
  border-color: hsl(180, 62%, 55%);
  background-origin: border-box;
  box-shadow: 5px;
  width: 300px;
  height: 200px;
  color: gray;
  margin-top: 200px;
  margin-left: 200px;
  border-radius: 5px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}
#colored-text {
  color: rgb(0, 0, 0);
}
#box2 {
  background-color: white;
  border-top-style: solid;
  border-color: hsl(0, 78%, 62%);
  border-radius: 5px;
  width: 300px;
  height: 200px;
  color: gray;
  position: absolute;
  top: 250px;
  left: 525px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}
#box3 {
  background-color: white;
  border-top-style: solid;
  border-color: hsl(34, 97%, 64%);
  border-radius: 5px;
  width: 300px;
  height: 200px;
  color: gray;
  position: absolute;
  top: 400px;
  left: 842px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}
#box4 {
  background-color: white;
  border-top-style: solid;
  border-color: hsl(212, 86%, 64%);
  border-radius: 5px;
  width: 300px;
  height: 200px;
  color: gray;
  position: absolute;
  left: 525px;
  top: 475px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}

@media screen and (max-width: 375px) {
  #app {
    flex-wrap: wrap;
    font-size: 15px;
    margin: 0 auto;
    width: auto;
  }
  #box1 {
    width: auto;
    margin-left: 0px;
    flex-wrap: wrap;
    margin-top: 15px;
  }
  #box2 {
    width: auto;
    margin-left: 0px;
    margin-top: 20px;
    flex-wrap: wrap;
    position: inherit;
  }
  #box3 {
    width: auto;
    margin-left: 0px;
    margin-top: 25px;

    flex-wrap: wrap;
    position: inherit;
  }
  #box4 {
    width: auto;
    margin-left: 0px;
    margin-top: 30px;
    flex-wrap: wrap;
    position: inherit;
  }
}
</style>
