<script>
  import {goto} from "$app/navigation";

  function handleClick()
  {
    goto('/')
  }
</script>

<button on:click={handleClick}>Back home!</button>