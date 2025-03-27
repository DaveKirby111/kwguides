<script>
  import { pageTitle } from "$lib/stores.js";
  pageTitle.set("Witcher 2: Assassins of Kings");
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
  <div class="guide-sections">
    <p class="fw-bold text-decoration-underline">Sections</p>
    <ul class="skip">
      <li><a href="#tombs">Side Quests</a></li>
    </ul>
  </div>

  <div id="side">
    <h3>side quests</h3>
  <div id="sideq">
    <p class="fw-bold text-decoration-underline">Little Sisters</p>
    <p>Order:</p>
    <ul class="sisters">
      <li>v</li>
      <li>diamond</li>
      <li>upside down v</li>
    </ul>
  </div>

  <div id="sideq">
    <p class="fw-bold text-decoration-underline">Gargoyle Contract</p>
    <p>Rune Order:</p>
    <ul class="runes">
      <li>left of the entrance</li>
      <li>right wall</li>
      <li>on the floor to the left</li>
      <li>on the floor in front of treasure chest</li>
    </ul>
  </div>
  </div>

  <a href="#top" class="skiplink">Top</a>
</div>

<style>
  h3{
    text-transform: capitalize;
  }

  #sideq{
    margin-bottom: 30px;
  }

.sisters {
text-transform: capitalize;
}
</style>
