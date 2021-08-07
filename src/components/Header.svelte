<div class="Header">
  <div class="Header-content">
    <div class="Header-menu">
      <nav>
        <ul class="navigation">
          <li><a href="./#/">Home</a></li>
          <li><a href="./#/skills">Skills</a></li>
          <li><a href="./#/projects">Projects</a></li>
          <li><a href="./#/contact">Contact</a></li>
        </ul>
      </nav>
      <nav>
        <ul class="social">
          <li>
            <a href="https://github.com/cldrojas"
              ><img src="./img/github.svg" alt="github" /></a
            >
          </li>
          <li>
            <a href="https://twitter.com/cld_rojas"
              ><img src="./img/twitter.svg" alt="twitter" /></a
            >
          </li>
          <li><img src="./img/discord.svg" alt="discord" /></li>
        </ul>
      </nav>
    </div>
  </div>
</div>

<style>
  .Header {
    position: relative;
    top: -10px;
    z-index: 10;
  }
  .Header-menu {
    background-color: transparent;
    display: flex;
    justify-content: space-between;
  }

  ul {
    display: flex;
  }

  li {
    height: 100%;
    list-style: none;
  }

  li:hover {
    cursor: pointer;
  }

  .navigation {
    padding: 0;
    line-height: 60px;
    height: 100%;
    font-size: 24px;
    margin: 0;
    width: 600px;
    justify-content: space-evenly;
    display: flex;
  }

  .social {
    width: 300px;
    justify-content: space-evenly;
    text-align: center;
  }

  .social img {
    height: 32px;
  }

  li > a {
    text-decoration: none;
    color: white;
    font-weight: bold;
  }
</style>
