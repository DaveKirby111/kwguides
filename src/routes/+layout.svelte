<script>
  import "$lib/app.css";
  import Nav from "$lib/nav.svelte";
  import kworld from "$lib/images/kworld.png";
</script>

<div class="container-fluid d-flex flex-column min-vh-100 m-0 p-0">
  <header>
    <div class="d-flex mb-5">
      <a href="/"><img src={kworld} alt="logo" class="logo" /></a>
      <Nav />
    </div>
    <h1 class="text-center">KWorld game guides</h1>
  </header>

  <main class="flex-grow-1">
    <slot />
  </main>

  <footer>
    <p>david kirby</p>
  </footer>
</div>
