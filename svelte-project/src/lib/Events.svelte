<!--<script>-->
<!--  export let handleClick-->
<!--</script>-->
<!--<button on:click={handleClick}>-->
<!--  Click me!-->
<!--</button>-->

<!--<div use:action="{handleClick}">Contenu</div>-->

<script>
  function handleMouseMove(event)
  {
    console.log(`x: ${event.clientX}, y: ${event.clientY}`)
  }
</script>

<div on:mousemove={handleMouseMove}>Hey, essaie de m'attraper!</div>