<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "final fantasy XIII";
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

  <ul class="skip">
    <p class="fw-bold text-decoration-underline">Sections</p>
    <li><a href="#chocobos">chocobos</a></li>
    <li><a href="#egg">growth egg</a></li>
    <li><a href="#characters">characters</a></li>
  </ul>

  <div class="chocobos" id="chocobos">
    <h4>chocobos</h4>

    <p class="fw-bold">How to unlock them</p>
    <p>Missions 1-8 then 12-14</p>
  </div>

  <div class="egg" id="egg">
    <h4>growth egg</h4>
    <p class="text-center">doubles CP</p>

    <p class="fw-bold">unlock:</p>
    <p>Mission 55 - complete mission 14 and unlock crystarium stage 9</p>
  </div>

  <div class="characters" id="characters">
    <h4>characters</h4>

    <div class="lightning">
      <h5>lightning</h5>

      <h6>primary roles</h6>
      <ul>
        <li>Commando</li>
        <li>Ravager</li>
        <li>Medic</li>
      </ul>

      <h6>eidolon</h6>
      <p>Odin</p>
    </div>

    <div class="sazh">
      <h5>sazh</h5>

      <h6>primary roles</h6>
      <ul>
        <li>Commando</li>
        <li>Ravager</li>
        <li>Synergist</li>
      </ul>

      <h6>eidolon</h6>
      <p>Brynhildr</p>
    </div>

    <div class="snow">
      <h5>snow</h5>

      <h6>primary roles</h6>
      <ul>
        <li>Commando</li>
        <li>Ravager</li>
        <li>Sentinel</li>
      </ul>

      <h6>eidolon</h6>
      <p>Shiva</p>
    </div>

    <div class="hope">
      <h5>hope</h5>

      <h6>primary roles</h6>
      <ul>
        <li>Ravager</li>
        <li>Synergist</li>
        <li>Medic</li>
      </ul>

      <h6>eidolon</h6>
      <p>alexander</p>
    </div>

    <div class="vanille">
      <h5>vanille</h5>

      <h6>primary roles</h6>
      <ul>
        <li>Ravager</li>
        <li>Saboteur</li>
        <li>Medic</li>
      </ul>

      <h6>eidolon</h6>
      <p>Hecatoncheir</p>
    </div>

    <div class="fang">
      <h5>fang</h5>

      <h6>primary roles</h6>
      <ul>
        <li>Commando</li>
        <li>Sentinel</li>
        <li>Saboteur</li>
      </ul>

      <h6>eidolon</h6>
      <p>Bahamut</p>
    </div>
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>
