<script>
    let count = 0;

    function increment()
    {
      count ++
    }
</script>

<p>Count: {count}</p>
<button on:click={increment}>Hey! Click me to increment!</button>