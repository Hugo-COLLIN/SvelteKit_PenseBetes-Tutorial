<script>
  export let text = "Click me!!!!"
</script>

<button on:click={() => alert("Button clicked")}>
  {text}
</button>