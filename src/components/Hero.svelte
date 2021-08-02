<script>
  import Header from "./Header.svelte";
</script>

<div class="Hero">
  <div class="Hero-content">
    <Header />
    <div class="Hero-elipse" />
    <div class="Hero-image">
      <img src="./img/hero.png" alt="Daniel Rojas" />
    </div>
    <div class="Hero-title">
      <h3>Hi, mi name is</h3>
      <h1>DANIEL ROJAS</h1>
      <h4>Full stack web developer</h4>
      <p>
        I’m a very curious man and passionate about new technologies, especially
        when its major features are precision and agility.
      </p>
      <p>In my free time i usually read, listen to music and go biking.</p>
    </div>
  </div>
</div>

<style>
  .Hero-content {
    height: 100vh;
    overflow: hidden;
  }

  .Hero-elipse {
    position: relative;
    z-index: -99;
    left: 53%;
    bottom: 34%;
    width: 1100px;
    height: 1100px;
    background: linear-gradient(
      216.39deg,
      rgba(0, 255, 209, 0.264) 10.19%,
      rgba(0, 107, 167, 0) 110.61%
    );
    border-radius: 550px;
    -moz-border-radius: 550px;
    -webkit-border-radius: 550px;
  }

  .Hero-image {
    width: 550px;
    height: 550px;
    position: absolute;
    display: flex;
    right: 0;
    bottom: 0;
  }

  .Hero-title {
    position: absolute;
    z-index: 1;
    top: 15%;
    left: 10%;
    margin: 10px;
    font-size: 30px;
    text-align: left;
    display: block;
    justify-content: left;
    width: 45%;
    height: 35%;
    padding: 10px;
  }

  .Hero-title h1 {
    color: #00dede;
    margin: 0;
    height: 20px;
  }
  .Hero-title h3 {
    height: 0;
    font-size: 30px;
  }
  .Hero-title h4 {
    margin-top: 50px;
    font-weight: 700;
    font-size: 24px;
  }
  .Hero-title p {
    text-align: justify;
    font-family: Poppins;
    font-style: normal;
    font-weight: 900;
    font-size: 22px;
    line-height: 33px;
    max-width: 477px;
  }
  @keyframes type {
    from {
      width: 0;
    }
  }

  @keyframes show {
    0% {
      opacity: 0;
      left: 100px;
    }

    100% {
      left: 0px;
    }
  }
</style>
