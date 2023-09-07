<script>
  import Nav from "$lib/nav.svelte";
  import kwg from "$lib/images/kwguides.jpg";
  import Title from "$lib/title.svelte";
</script>

<header id="top" class="d-flex flex-column flex-md-row">
  <div class="title d-flex justify-content-center p-3">
    <a href="/"><img src={kwg} alt="logo" class="logo" /></a>
  </div>

  <div class="w-100" id="menu"><Nav /></div>
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

  .logo:hover {
    box-shadow: 5px 5px 5px red;
  }

  header {
    background-image: url("$lib/images/space.webp");
    background-size: 100% 100%;
  }

  .page {
    background-color: rgb(0, 206, 0);
  }
</style>
