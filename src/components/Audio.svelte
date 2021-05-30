<script>
  export let audioRef;
</script>

<!-- svelte-ignore a11y-media-has-caption -->
<audio bind:this={audioRef} autoplay controls loop>
  <source src="/feelings.mp3" type="audio/mpeg" />
  <source src="/feelings.m4a" />
</audio>

<style>
  audio {
    margin: auto;
  }
</style>
