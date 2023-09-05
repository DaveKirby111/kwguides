<script>
  import Nav from "$lib/nav.svelte";
  import kwg from "$lib/images/kwguides.jpg";
  import Title from "$lib/title.svelte";
</script>

<header id="top" class="d-flex flex-column flex-md-row">
  <div class="title d-flex justify-content-center">
    <a href="/"><img src={kwg} alt="logo" class="logo" /></a>
  </div>
  <div class="mx-auto w-100"><Nav /></div>
</header>

<div class="page">
  <Title />
</div>

<style>
  .logo {
    width: 200px;
    height: 90px;
    margin-left: 10px;
    margin-top: 10px;
  }
</style>
