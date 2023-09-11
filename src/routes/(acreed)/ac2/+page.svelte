<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "assassin's creed II";
  import Sections from "$lib/sections.svelte";

  import glyph1 from "$lib/images/ac/ac2/florence.jpg";
  import glyph2 from "$lib/images/ac/ac2/villa.jpg";
  import glyph3 from "$lib/images/ac/ac2/tuscany.jpg";
  import glyph4 from "$lib/images/ac/ac2/forli.jpg";
  import statues from "$lib/images/ac/ac2/statues.webp";

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
    <li><a href="#statues">statues</a></li>
    <li><a href="#glyphs">glyphs</a></li>
  </ul>

  <div class="statues" id="statues">
    <h4>statue locations</h4>
    <img src={statues} alt="statues" />
  </div>

  <div class="glyphs" id="glyphs">
    <h4>glyph locations</h4>

    <h5>florence</h5>
    <img src={glyph1} alt="glyph" />

    <h5>villa monteriggioni</h5>
    <img src={glyph2} alt="glyph" />

    <h5>tuscany</h5>
    <img src={glyph3} alt="glyph" />

    <h5>forli</h5>
    <img src={glyph4} alt="glyph" />
  </div>

  <a href="#top" class="skiplink">Top</a>
</div>

<style>
  /* img {
    width: 900px;
    height: 500px;
  } */
</style>
