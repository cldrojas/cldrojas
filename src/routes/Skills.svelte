<script>
  import Skill from "../components/Skill.svelte";
</script>

<div class="Skills">
  <div class="Skills-container">
    <div class="Skills-content">
      <div class="Skills-set">
        <div class="Skills-title">
          <h2>Frontend</h2>
        </div>
        <div class="Skills-list">
          <Skill name={"HTML"} src={"./img/html.svg"} />
          <Skill name={"CSS"} src={"./img/css.svg"} />
          <Skill name={"JavaScript"} src={"./img/javascript.svg"} />
          <Skill name={"Svelte"} src={"./img/svelte.svg"} />
        </div>
      </div>
      <div class="Skills-set">
        <div class="Skills-title">
          <h2>Backend</h2>
        </div>
        <div class="Skills-list">
          <Skill name={"Php"} src={"./img/php.svg"} />
          <Skill name={"MySql"} src={"./img/mysql.svg"} />
          <Skill name={"MongoDb"} src={"./img/mongo.svg"} />
          <Skill name={"Node.js"} src={"./img/node.svg"} />
        </div>
      </div>
      <div class="Skills-set">
        <div class="Skills-title">
          <h2>Design</h2>
        </div>
        <div class="Skills-list">
          <Skill name={"Figma"} src={"./img/figma.svg"} />
          <Skill name={"PhotoShop"} src={"./img/photoshop.svg"} />
        </div>
      </div>
      <div class="Skills-set">
        <div class="Skills-title">
          <h2>Others</h2>
        </div>
        <div class="Skills-list">
          <Skill name={"Git"} src={"./img/git.svg"} />
          <Skill name={"Terminal"} src={"./img/terminal.svg"} />
          <Skill name={"Firebase"} src={"./img/firebase.svg"} />
          <Skill name={"Flutter"} src={"./img/flutter.svg"} />
        </div>
      </div>
    </div>
  </div>
</div>

<style>
  .Skills {
    position: relative;
    height: 100vh;
  }

  .Skills-content {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 100px;
    width: 100%;
  }
  .Skills-set:nth-child(odd) {
    animation: 1.7s ease-in-out 1 topFadeIn;
  }
  .Skills-set:nth-child(even) {
    animation: 2.3s ease-in-out 1 topFadeIn;
  }

  .Skills-set {
    padding: 10px;
  }

  .Skills-title {
    display: flex;
    justify-content: center;
  }

  .Skills-list {
    display: flex;
    justify-content: space-evenly;
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
</style>
