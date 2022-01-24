<script>
  import "../app.postcss";
  import { messageIcon } from "$lib/icons";
</script>

<h1>Welcome to SvelteKit</h1>
<p>
  Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation
</p>
<div class="ml-s8 fill-current justify-end">
  {@html messageIcon}
</div>

<style lang="postcss">
  h1 {
    color: var(--col-red);
  }
</style>
