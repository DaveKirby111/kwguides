<script>
  import "$lib/app.css";
  import Nav from "$lib/nav.svelte";
  import kwg from "$lib/images/kwguides.jpg";
  import Title from "$lib/title.svelte";
</script>

<svelte:head>
  <title>KWorld Game Guides</title>
</svelte:head>

<div class="container-fluid d-flex flex-column min-vh-100 m-0 p-0">
  <header>
    <div class="title d-flex">
      <a href="/"><img src={kwg} alt="logo" class="logo" /></a>
      <Nav />
    </div>
    <Title />
  </header>

  <main class="flex-grow-1">
    <slot />
  </main>

  <footer>
    <p>david kirby</p>
  </footer>
</div>
