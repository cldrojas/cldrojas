<script>
  export let name, src;
</script>

<div class="Skill">
  <div class="Skill-container">
    <div class="Skill-content">
      <div class="Skill-image">
        <img {src} alt={name} />
      </div>
      <div class="Skill-title">
        <h3>{name}</h3>
      </div>
    </div>
  </div>
</div>

<style>
  .Skill-image {
    display: flex;
    justify-content: center;
    text-align: center;
  }
  .Skill-title {
    display: flex;
    line-height: 0;
    justify-content: center;
  }
</style>
