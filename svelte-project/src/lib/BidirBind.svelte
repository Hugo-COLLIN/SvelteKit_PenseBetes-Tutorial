<script>
  let nom = "Lucas"
</script>

<input bind:value={nom}/>

<h1>Salut {nom}!</h1>

<button on:click={()=>nom=""}>Erase...</button>