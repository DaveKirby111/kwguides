<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "assassin's creed origins";
  import Sections from "$lib/sections.svelte";

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

  <a href="#top" class="skiplink">Top</a>
</div>

<style>
</style>
