<script>
  export let primary = false;
  export let hover = false;
  export let blue = false;
</script>

<button class="button" class:primary class:hover>
  <slot />
</button>

<style>
  .button {
    @apply mx-2 py-2 px-14 text-white border-1 border-gray-500 rounded-lg border-solid;
  }
  .primary {
    @apply bg-gradient-26 border-none;
  }
  .hover {
    @apply text-gray-400 hover:text-white hover:bg-gradient-26 hover:border-transparent hover:transition hover:duration-500;
  }
</style>
