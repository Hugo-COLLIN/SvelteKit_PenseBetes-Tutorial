<script>
  let active=false
</script>

<div class:active>
  <p>Elt actif</p>
  <button on:click={()=>active=!active}>Toggle!</button>
</div>

<style>
    .active {
        background-color: #ff3e00;
        color: white;
    }
</style>