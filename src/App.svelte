<script>
  import NavBar from "./components/NavBar.svelte";
  import Hero from "./components/Hero.svelte";
  export let name;
</script>

<NavBar />
<Hero />
<main class="pt-20 text-center">
  <h1>Hello {name}!</h1>
  <p>
    Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn
    how to build Svelte apps.
  </p>
</main>

<style windi:preflights:global windi:safelist:global>
  a {
    @apply text-blue-400 underline;
  }
</style>
