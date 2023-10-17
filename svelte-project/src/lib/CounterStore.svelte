<script>
  import {count} from './store.js'

  // on précède les variables du store par $ pour y accéder et les modifier
  function increment() {
    $count++; // $ pour avoir la valeur de l'objet
  }

  function decrement() {
    $count--; // $ pour avoir la valeur de l'objet
  }
</script>

<button on:click={increment}>+</button>
<p>{$count}</p><!-- $ pour avoir la valeur de l'objet-->
<button on:click={decrement}>-</button>