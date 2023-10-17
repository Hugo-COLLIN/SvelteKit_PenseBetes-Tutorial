<script>
  import { page } from '$app/stores';
  $: console.log($page.params); //is the $: useful?
</script>

<h1>User {$page.params.id}</h1>

<!-- from https://github.com/sveltejs/kit/discussions/8855#discussioncomment-4854313 -->