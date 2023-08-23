<script>
  import Nav from "$lib/nav.svelte";
  import kwg from "$lib/images/kwguides.jpg";
  import Title from "$lib/title.svelte";
</script>

<header>
  <div class="title d-flex">
    <a href="/"><img src={kwg} alt="logo" class="logo" /></a>
    <Nav />
  </div>
  <Title />
</header>

<style>
  .logo {
    width: 200px;
    height: 90px;
    margin-left: 10px;
  }
</style>
