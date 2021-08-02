<script>
  import Hero from "./components/Hero.svelte";
</script>

<div class="App">
  <div class="App-content">
    <Hero />
  </div>
</div>

<style>
  @import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;700;900&display=swap");
  .App {
    font-family: "Poppins", sans-serif;
    height: 100%;
    overflow: hidden;
  }
  .App-content {
    margin: 0 auto;
  }
</style>
