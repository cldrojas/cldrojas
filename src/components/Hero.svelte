<div class="Hero">
  <div class="Hero-content">
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
  .Hero {
    height: 100vh;
  }
  .Hero-image {
    display: flex;
    position: relative;
    width: 550px;
    height: 550px;
    float: right;
    top: 27px;
    animation: 2s ease-in-out 0s 1 rightFadeIn;
  }

  .Hero-title {
    display: block;
    width: 45%;
    height: 35%;
    margin: 10px;
    padding: 10px;
    position: relative;
    top: 15%;
    left: 10%;
    font-size: 30px;
    text-align: left;
    justify-content: left;
    animation: 2s ease-in-out 1 topFadeIn;
  }

  .Hero-title h3 {
    height: 0;
    font-size: 30px;
  }
  .Hero-title h1 {
    height: 20px;
    margin: 0;
    color: #00dede;
  }
  .Hero-title h4 {
    margin-top: 50px;
    font-size: 24px;
    font-weight: 700;
  }
  .Hero-title p {
    max-width: 477px;
    line-height: 33px;
    text-align: justify;
    font-size: 22px;
    font-weight: 900;
    font-style: normal;
  }

  @keyframes topFadeIn {
    0% {
      opacity: 0;
      transform: translateY(-20px);
    }
    100% {
      opacity: 1;
      transform: translateY(0);
    }
  }

  @keyframes rightFadeIn {
    0% {
      opacity: 0;
      transform: translateX(-10px);
    }
    100% {
      opacity: 1;
      transform: translateX(0);
    }
  }
</style>
