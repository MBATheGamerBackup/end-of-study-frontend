<script>
  import { authenticated } from "$lib/store/stores";
</script>

<svelte:head>
  <title>{$authenticated ? "Profil Setting" : "Not Found"}</title>
</svelte:head>

<slot />
