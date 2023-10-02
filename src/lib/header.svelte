<script>
  import Nav from "$lib/nav.svelte";
  import kwg from "$lib/images/kwguides.jpg";
  import Title from "$lib/title.svelte";
  import Navbar from "./navbar.svelte";
</script>

<!-- <div class="w-100" id="menu">
  <a href="/"><img src={kwg} alt="logo" class="logo" /></a>
  <Navbar />
</div> -->

<header id="top">
  <!-- <div class="title d-flex justify-content-center p-3">
    <a href="/"><img src={kwg} alt="logo" class="logo" /></a>
  </div> -->

  <div id="menu">
    <Navbar />
  </div>
  <a href="/"><img src={kwg} alt="logo" class="logo" /></a>
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
    /* flex-direction: column !important; */
  }

  .page {
    background-color: rgb(0, 206, 0);
  }

  @media screen and (max-width: 600px) {
    .title img {
      display: block;
      margin: auto;
    }
  }

  @media screen and (max-width: 900px) {
    header {
      flex-direction: column !important;
    }

    .title img {
      display: block;
      margin: auto;
    }
  }
</style>
