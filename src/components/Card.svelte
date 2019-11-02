<script>
  import Avatar from "./Avatar.svelte";
</script>

<style>
  .card {
    display: flex;
    justify-content: center;
  }

  .card__data {
    display: flex;
    flex-direction: column;
    justify-content: center;

    padding: var(--d-spacing);
  }

  .card__name {
    font-size: 2em;

    color: var(--c-black);
  }

  .card__subtitle {
    margin-top: var(--d-spacing-half);

    font-size: 1.2em;

    color: var(--c-dark-grey);
  }
</style>

<div class="card">
  <Avatar src="./assets/avatar.jpg" alt="Profile picture of Benjamin Naesen" />
  <div class="card__data">
    <p class="card__name">Benjamin Naesen</p>
    <p class="card__subtitle">Full Stack JavaScript Developer</p>
  </div>
</div>
