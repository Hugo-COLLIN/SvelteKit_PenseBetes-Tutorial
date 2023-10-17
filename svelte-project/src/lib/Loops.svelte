<script>
  let films = [
    { titre: 'Titanic', annee: 1997 },
    { titre: 'Le Roi Lion', annee: 1994 },
    { titre: 'La Liste de Schindler', annee: 1993 },
  ]
</script>

<ul>
  {#each films as film}
    <li>{film.titre} : {film.annee}</li>
  {/each}
</ul>