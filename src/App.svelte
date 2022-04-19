<script>
  import { onMount } from 'svelte';

  let sveeg;

  onMount(() => {
    panzoom(sveeg);
  });
</script>

<svg bind:this={sveeg}>
  <g id='scene'> 
    <circle cx='100' cy='100' r='50' fill='pink'></circle>
  </g>
</svg>

<style>
</style>

