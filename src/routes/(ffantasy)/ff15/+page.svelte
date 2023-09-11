<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "final fantasy XV";
  import Sections from "$lib/sections.svelte";
  import tombs from "$lib/images/ff15/15tombs.jpg";

  const sections = [
    {
      name: "guides",
      link: "#guides",
    },
  ];
</script>

<Sections {sections} />

<div id="guides" class="guides">
  <h2>guides</h2>

  <ul class="skip">
    <p class="fw-bold text-decoration-underline">Sections</p>
    <li><a href="#tombs">tombs</a></li>
  </ul>

  <div class="tombs" id="tombs">
    <h3 class="text-center">royal tombs</h3>
    <img src={tombs} alt="tombs" />
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<style>
  .tombs img {
    display: block;
    margin: auto;
  }
</style>
