<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "final fantasy XIII";
  import Sections from "$lib/sections.svelte";

  const sections = [
    {
      name: "mods",
      link: "#mods",
    },

    {
      name: "guides",
      link: "#guides",
    },
  ];
</script>

<Sections {sections} />

<div id="mods" class="mods">
  <h2>mods</h2>
</div>

<div id="guides" class="guides">
  <h2>guides</h2>
</div>
