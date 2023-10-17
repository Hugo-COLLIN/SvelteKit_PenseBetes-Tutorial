<script>
  let name = ''
  let email = ''

  function handleSubmit()
  {
    console.log('Submitted:', {name,email})
  }
</script>


<form on:submit|preventDefault={handleSubmit}>
  <label>
    Nom:
    <input bind:value={name}>
  </label>
  <label>
    Email:
    <input bind:value={email} type="email">
  </label>
  <button type="submit">Soumettre!</button>
</form>