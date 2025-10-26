<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "Final Fantasy XII";
  import Sections from "$lib/sections.svelte";
  import gcrystal from "$lib/images/ff12/GreatCrystal.png";

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
      <li><a href="#crystal">great crystal</a></li>
      <li><a href="#ultima">ultima</a></li>
      <li><a href="#monographs">monographs</a></li>
    </ul>
  </div>

  <div class="greatcrystal mb-5" id="crystal">
    <h4>Great Crystal</h4>
    <a href={gcrystal} target="_blank" rel="noopener noreferrer">
      <img src={gcrystal} alt="crystal" class="crystal" />
    </a>
  </div>

  <div class="ultima mb-5" id="crystal">
    <h4>Ultima</h4>

    <p>
      You need to obtain a White Masks or a Sage’s Ring for each of your
      characters before you head to the Great Crystal. Some of your characters
      may not be able to wear a White Mask, but they can all wear a Sage’s Ring,
      so your best bet is to obtain one or two of them in addition to a White
      Mask.
    </p>

    <p class="fw-bold">White Masks:</p>

    <ol>
      <li>Cerobi Steppe = North Liavell Hills area, rng treasure chest</li>
      <li>Necrohol of Nabudis = Cloister of Distant Song, chest</li>
      <li>Bazaar = White Vestaments</li>
      <ul>
        <li>Blood Wool = 9</li>
        <li>Beastlord Hide = 7</li>
        <li>Aquarius Gem = 4</li>
      </ul>
    </ol>

    <p class="fw-bold">Sage's Ring:</p>

    <ol>
      <li>Henne Mines = phase 2 shaft</li>
      <li>Stilshrine of Miriam = Ward of Steel.</li>
      <li>Subterra</li>
    </ol>

    <div class="ultima-boss p-3" id="ultima">
      <h5 class="text-center">Boss Battle: Ultima</h5>

      <ul>
        <li>
          <p class="fw-bold">Level:</p>
          63
        </li>
        <li>
          <p class="fw-bold">HP:</p>
          258,001
        </li>
        <li>
          <p class="fw-bold">Steal:</p>
          Virgo Gem, Elixir, High Arcana
        </li>
      </ul>

      <p>
        Equip each character with items that absorb Holy. Switch to weapons that
        deal Dark damage. Ultima will activate a Magic Barrier at 70% HP. Ultima
        can cause the following effects:
      </p>

      <ul>
        <li>HP Drain = will slowly drain HP of all party members</li>
        <li>MP Drain = will slowly drain MP of all party members</li>
        <li>No Attack = will disable attack command</li>
        <li>No Magick = will disable magic</li>
        <li>No Technicks = disable technicks</li>
        <li>No Items = disable items</li>
        <li>Gravity Field = slow down time (similar to slow)</li>
      </ul>

      <p>
        Keep your status enhancing spells active to deal with HP Drain
        throughout the fight. This includes Protect, Bubble and Shell. MP Drain
        can be dealt with using Ethers (if required). Switch out the “Attack”
        command with the Telekinesis to allow your characters to continue doing
        damage.
      </p>

      <p>
        Keep your status enhancing spells active to deal with HP Drain
        throughout the fight. This includes Protect, Bubble and Shell. MP Drain
        can be dealt with using Ethers (if required). Switch out the “Attack”
        command with the Telekinesis to allow your characters to continue doing
        damage.
      </p>

      <p>
        Make sure to Dispel her and have a Gambit to continue Dispelling active
        throughout the fight. You will also have to watch for when she casts
        Reflectga on your party.
      </p>

      <p>
        In addition to preventing you from casting healing spells on yourself,
        Ultima will also cast curative Magick on your party members while
        Reflect is active allowing her to heal herself. You will have to Dispel
        Reverse as well if she casts it on your party members as she will follow
        it up quickly with Renew which will reduce them to 1 HP (and likely
        cause them to kill themselves with their next attack).
      </p>
    </div>
  </div>

  <div class="monographs" id="monographs">
    <h4 class="mb-5">Monographs</h4>

    <p>
      The last important thing to note is that you should make every attempt to
      begin purchasing the various Monographs/Grimoires that are available for
      sale. Each of the Grimoires become available for purchase from the Bazaar
      and increase the quality of loot you receive from destroying specific
      types of enemies.
    </p>

    <p>Knight's Monograph = 19,000 gil, talk to weapon shop owner 30 times</p>
    <p>Warmage Monograph = 20,000 gil, read Sandsea notice board 20 times</p>
    <p>Mage's Monograph = 21,000 gil, talk to magick shop owner 25 times</p>
    <p>Scholar's Monograph = 22,000 gil, talk to armor shop owner 15 times</p>
    <p>
      Dragoon's Monograph = 22,000 gil, read notice board in sandsea 40 times
    </p>
    <p>Sage's Monograph = 25,000 gil, talk to any shop owner 100 times</p>
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<style>
  .crystal {
    width: 300px;
    height: 450px;
  }

  .greatcrystal img {
    display: block;
    margin: auto;
  }

  @media screen and (max-width: 600px) {
    div {
      padding: 5px;
    }
  }
</style>
