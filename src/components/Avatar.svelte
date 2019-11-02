<script>
  export let src, alt;
</script>

<style>
  .avatar {
    height: 100px;
    width: 100px;

    padding: var(--d-spacing);

    border-radius: 50%;
  }
</style>

<img class="avatar" {src} {alt} />
