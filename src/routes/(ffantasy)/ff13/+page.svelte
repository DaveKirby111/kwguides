<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "Final Fantasy XIII";
  import Sections from "$lib/sections.svelte";

  // const sections = [
  //   {
  //     name: "guides",
  //     link: "#guides",
  //   },
  // ];
</script>

<!-- <Sections {sections} /> -->

<div id="guides" class="guides">
  <h2>guides</h2>

  <div class="guide-sections">
    <p class="fw-bold text-decoration-underline">Sections</p>
    <ul class="skip">
      <li><a href="#trophies">trophies</a></li>
      <li><a href="#chocobos">chocobos</a></li>
      <li><a href="#egg">growth egg</a></li>
      <li><a href="#characters">characters</a></li>
    </ul>
  </div>

  <div id="trophies">
    <h4>trophies</h4>
    <h5>100% completionist</h5>
    <div class="d-flex">
      <div>
        <ul>
          <li>ultimate hero</li>
          <p>Acquired all trophies.</p>
          <li>instrument of fate</li>
          <p>Took the first steps toward challenging an unjust fate.</p>
          <li>instrument of dissent</li>
          <p>Survived the Purge to confront a greater peril.</p>
          <li>instrument of tragedy</li>
          <p>Strode into danger's den and paid the consequences.</p>
          <li>instrument of flight</li>
          <p>Slipped through the net and lived to fight another day.</p>
          <li>instrument of vengeance</li>
          <p>Resolved to be more than a victim of circumstance.</p>
          <li>instrument of survival</li>
          <p>Evaded pursuers, though memories of the past still gave chase.</p>
          <li>instrument of rebellion</li>
          <p>Made plans to infiltrate enemy-occupied territory.</p>
          <li>instrument of shame</li>
          <p>Carried the burden of guilt to the end of the line.</p>
          <li>instrument of wrath</li>
          <p>Took the fight to the enemy's door.</p>
          <li>instrument of truth</li>
          <p>Recognized the true threat to the world's future.</p>
          <li>instrument of hope</li>
          <p>Traveled to the world below, seeking a way to alter fate.</p>
          <li>instrument of faith</li>
          <p>Defied destiny's charge and embarked on a different path.</p>
          <li>instrument of change</li>
          <p>Witnessed the dawn of a new crystal legend.</p>
          <li>pulsian pioneer</li>
          <p>Took over 10,000 steps on the lowerworld surface.</p>
          <li>gysahl wreath</li>
          <p>Discovered buried treasure with a little help from a chocobo.</p>
          <li>kelger's cup</li>
          <p>Completed all low-level Cie'th Stone missions.</p>
          <li>xezat's chalice</li>
          <p>Completed all mid-level Cie'th Stone missions.</p>
        </ul>
      </div>
      <div>
        <ul>
          <li>exorcist</li>
          <p>Triumphed over undying lowerworld souls in seven fierce battles.</p>
          <li>floraphobe</li>
          <p>Toppled a green terror and cut an oversized succulent down to size.</p>
          <li>natural selector</li>
          <p>Passed Titan's trials.</p>
          <li>dorgann's trophy</li>
          <p>Completed all high-level Cie'th Stone missions.</p>
          <li>galuf's grail</li>
          <p>Completed all Cie'th Stone missions.</p>
          <li>L'Cie paragon</li>
          <p>Earned a 5-star rating for all Cie'th Stone missions.</p>
          <li>commander's seal</li>
          <p>Mastered the Commando role.</p>
          <li>ravager's seal</li>
          <p>Mastered the Ravager role.</p>
          <li>sentinel's seal</li>
          <p>Mastered the Sentinel role.</p>
          <li>saboteur's seal</li>
          <p>Mastered the Saboteur role.</p>
          <li>synergist's seal</li>
          <p>Mastered the Synergist role.</p>
          <li>medic's seal</li>
          <p>Mastered the Medic role.</p>
          <li>limit breaker</li>
          <p>Dealt 100,000+ damage with a single attack.</p>
          <li>adamant will</li>
          <p>Felled a heavyweight of the lowerworld wilds.</p>
          <li>master's seal</li>
          <p>Fully developed all characters.</p>
          <li>treasure hunter</li>
          <p>Held every weapon and accessory.</p>
          <li>loremaster</li>
          <p>Discerned the full attributes of 100 enemies.</p>
          <li>superstar</li>
          <p>arned a 5-star rating in the battle to determine the world's fate.</p>
        </ul>
      </div>
    </div>
  </div>

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

<style>

ul li {
      text-transform: capitalize;
    }

    ul p {
      text-transform: capitalize;
      font-size: 12px;
    }

  @media screen and (max-width: 600px) {
    div {
      padding: 5px;
    }
  }
</style>
