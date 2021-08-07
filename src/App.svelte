<script>
  import Router from "svelte-spa-router";
  import Header from "./components/Header.svelte";

  import Home from "./routes/Home.svelte";
  import Skills from "./routes/Skills.svelte";
</script>

<div class="App">
  <div class="App-elipse" />
  <div class="App-content">
    <Header />
    <Router
      routes={{
        "/": Home,
        "/skills": Skills,
      }}
    />
  </div>
</div>

<style>
  @import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;700;900&display=swap");
  .App {
    height: 100vh;
    font-family: "Poppins", sans-serif;
    overflow: hidden;
  }
  .App-content {
    height: 100%;
    position: relative;
    bottom: 164vh;
  }
  .App-elipse {
    position: relative;
    width: 1100px;
    height: 1100px;
    left: 53%;
    bottom: 34%;
    z-index: -1;
    background: linear-gradient(
      216.39deg,
      rgba(0, 255, 209, 0.264) 10.19%,
      rgba(0, 107, 167, 0) 110.61%
    );
    border-radius: 550px;
    -moz-border-radius: 550px;
    -webkit-border-radius: 550px;
  }
</style>
