<script>
  let loggedIn = false;
</script>

{#if loggedIn}
  <p>Bienvenue!</p>4
{:else}
  <p>Déconnecté!</p>
{/if}