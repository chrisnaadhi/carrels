<script>
  import Button from "./../shared/Button.svelte";
  let primary = true;
  let hover = true;
  let blue = true;
</script>

<section id="hero" class="h-xl object-fit">
  <div
    id="cover"
    class="h-xl flex justify-center bg-opacity-50 bg-black text-center mx-auto"
  >
    <div id="hero-content" class="my-auto">
      <h1 class="hero-title md:text-10xl">Carrels</h1>
      <p class="text-gray-200 text-2xl italic subtitle">
        Help your study relaxed and joyful
      </p>
      <div class="button-group">
        <Button {primary}>Explore</Button>
        <Button {hover} {blue}>About Us</Button>
      </div>
    </div>
  </div>
</section>

<style>
  #hero {
    background: url("./../images/carrels-bg.jpg");
  }
  #cover {
    background: rgba(0, 0, 0, 0.75);
  }
  .hero-title {
    font-family: "Carattere", cursive;
    @apply font-extrabold text-9xl bg-gradient-26 bg-clip-text text-transparent;
  }
  .subtitle {
    font-family: "Noto Sans JP", sans-serif;
  }
  .button-group {
    @apply mt-5 space-x-3;
  }
</style>
