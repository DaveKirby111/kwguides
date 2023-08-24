<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "elder scrolls V: skyrim";
  import Sections from "$lib/sections.svelte";
  import * as components from "$lib/skyrimarr.js";

  const sections = [
    {
      name: "console",
      link: "#console",
    },

    {
      name: "bat",
      link: "#bat",
    },

    {
      name: "mods",
      link: "#mods",
    },

    {
      name: "guides",
      link: "#guides",
    },
  ];

  const commands = [
    {
      name: "god mode",
      input: "tgm",
      desc: "toggle god mode. Infinite health, magicka, fatigue",
    },

    {
      name: "toggle collision",
      input: "tcl",
      desc: "move through the world.",
    },

    {
      name: "money",
      input: "player.additem f (amount)",
      desc: "give the player gold",
    },

    {
      name: "grand soul gems",
      input: "player.additem 2e4ff (amount)",
      desc: "give the player filled grand soul gems",
    },

    {
      name: "ultimate healing potions",
      input: "player.additem 30be5 (amount)",
      desc: "gives highest quality healing potions",
    },

    {
      name: "dragon souls",
      input: "player.modav dragonsouls (amount)",
      desc: "gives dragon souls for shouts",
    },

    {
      name: "dragon aspect",
      input: "player.teachword 0401df93, 94, 95",
      desc: "all words for dragon aspect shout",
    },
  ];
</script>

<Sections {sections} />

<div id="console" class="console">
  <h2>console commands</h2>

  <table class="table table-responsive">
    <thead class="text-capitalize">
      <tr>
        <th>name</th>
        <th>command</th>
        <th>function</th>
      </tr>
    </thead>
    <tbody>
      {#each commands as command}
        <tr>
          <td>{command.name}</td>
          <td>{command.input}</td>
          <td>{command.desc}</td>
        </tr>
      {/each}
    </tbody>
  </table>
</div>

<div id="bat" class="bat">
  <h2>bat files</h2>
  <p class="fw-bold">What are they?</p>
  <p>
    Bat files are .txt files containing console commands and placed in the games
    root folder. Bringing up the console in game and using the input bat
    (filename) will execute the console commands in that .txt file.
  </p>
</div>

<div id="mods" class="mods">
  <h2>mods</h2>

  <div class="d-flex mb-5 justify-content-center">
    <div class="d-flex flex-column me-5 text-center">
      <p>Skyrim Script Extender</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/30379?tab=description"
          target="_blank">Nexus Page</a
        >
      </p>
    </div>
    <div class="d-flex flex-column me-5 text-center">
      <p>SkyUI</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/12604?tab=description"
          target="_blank">Nexus Page</a
        >
      </p>
    </div>
    <div class="d-flex flex-column me-5 text-center">
      <p>Unofficial Skyrim Special Edition Patch</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/266?tab=files&file_id=392477"
          target="_blank">Nexus Page</a
        >
      </p>
    </div>
    <div class="d-flex flex-column me-5 text-center">
      <p>Unofficial Skyrim Creation Club Patches</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/18975?tab=description"
          target="_blank">Nexus Page</a
        >
      </p>
    </div>
    <div class="d-flex flex-column me-5 text-center">
      <p>SkyHud</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/463?tab=description"
          target="_blank">Nexus Page</a
        >
      </p>
    </div>
    <div class="d-flex flex-column me-5 text-center">
      <p>Nordic UI Overhaul</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/49881?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
  </div>
  <div class="d-flex mb-5 justify-content-center">
    <div class="d-flex flex-column me-5 text-center">
      <p>Werewolf Perks Expanded</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/1285?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>Dragon Aspect (Mage Version)</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/22763?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>My home is your home</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/7096?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>Paarthurnax Quest Expansion</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/51711?tab=description"
          target="_blank">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>Cloaks of Skyrim</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/6369?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>Armor Variants Expansion</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/34100?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
  </div>
  <div class="d-flex justify-content-center">
    <div class="me-5 text-center">
      <p>Convenient Horses</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/9519?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>Sleek Wolf Armor</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/44812?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>Perk Point Book</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/2254?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>Magic Training</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/40000?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>Alternate Start - Live Another Life</p>
      <p style="color: red;">* Requires Unofficial Patch *</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/272?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>A Quality World Map</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/5804?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
  </div>
</div>
<div id="guides" class="guides">
  <h2>guides</h2>

  <div class="goldbrand">
    <h4>A Matter of Pride: Goldbrand</h4>

    <ol>
      <li>Start quest:</li>
      <ul>
        <li>Boethia's Shrine = find Eranya's Journal</li>
        <li>College of Winterhold = find Eranya's Research Notes</li>
      </ul>
      <li>Find Sivdur's Amulet = Whiterun, Lars Battle-Born</li>
      <li>Find Magrathi's Skull = Ivarstead, Shroud Hearth Barrow</li>
      <li>Travel to Sivdur's Respite</li>
      <li>Locate Goldbrand</li>
    </ol>
  </div>

  <div class="shouts">
    <h4>Dragon Shouts</h4>

    <div class="d-flex">
      <div class="shout">
        <p class="fw-bold">Animal Allegiance</p>

        <ul>
          <li><a href={components.ascent}>Ancient's Ascent</a></li>
          <li><a href={components.angar}>Angarvunde</a></li>
          <li>Ysgramor's Tomb (Companions quest)</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Aura Whisper</p>

        <ul>
          <li><a href={components.northwind}>Northwind Summit</a></li>
          <li><a href={components.valthume}>Valthume</a></li>
          <li><a href={components.volunruud}>Volunruud</a></li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Battle Fury</p>

        <ul>
          <li><a href={components.vahlok}>Vahlok's Tomb</a></li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Become Ethereal</p>

        <ul>
          <li><a href={components.ironbind}>Ironbind Barrow</a></li>
          <li><a href={components.lost}>Lost Valley Redoubt</a></li>
          <li>Ustengrav (main quest)</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Bend Will</p>

        <ul>
          <li>Dragonborn- Main Quest</li>
        </ul>
      </div>
    </div>
    <div class="d-flex">
      <div class="shout">
        <p class="fw-bold">Call Dragon</p>

        <ul>
          <li>Main Quest</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Call of Valor</p>

        <ul>
          <li>Sovngarde - Main Quest</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Clear Skies</p>

        <ul>
          <li>High Hrothgar - Main Quest</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Cyclone</p>

        <ul>
          <li><a href={components.benk}>Benkongerike</a></li>
          <li><a href={components.kol}>Kolbjorn Barrow</a></li>
          <li><a href={components.wridge}>White Ridge Sanctum</a></li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Disarm</p>

        <ul>
          <li><a href={components.eldersblood}>Eldersblood Peak</a></li>
          <li><a href={components.silverdrift}>Silverdrift Lair</a></li>
          <li>Snow Veil Sanctum (thieves guild)</li>
        </ul>
      </div>
    </div>
    <div class="d-flex">
      <div class="shout">
        <p class="fw-bold">Dismay</p>

        <ul>
          <li>Dead Crone Rock</li>
          <li>Lost Tongue Overlook</li>
          <li>Shalidor's Maze, Labyrinthian</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Dragon Aspect</p>

        <ul>
          <li>Raven Rock Mine</li>
          <li>Temple of Miraak</li>
          <li>Apocrypha</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Dragonrend</p>

        <ul>
          <li>Main Quest</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Drain Vitality</p>

        <ul>
          <li>Arcwind Point</li>
          <li>Dawnguard - Main Quest</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Elemental Fury</p>

        <ul>
          <li>Dragontooth Crater</li>
          <li>Shriekwind Bastion</li>
          <li>Statue of Meridia</li>
        </ul>
      </div>
    </div>
    <div class="d-flex">
      <div class="shout">
        <p class="fw-bold">Fire Breath</p>

        <ul>
          <li>Dustman's Cairn (Companion's Quest)</li>
          <li>Sunderstone Gorge</li>
          <li>Main Quest</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Frost Breath</p>

        <ul>
          <li>Bonestrewn Crest</li>
          <li>Folgunthur</li>
          <li>Skyborn Altar</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Ice Form</p>

        <ul>
          <li>Frostmere Crypt</li>
          <li>Mount Anthor</li>
          <li>Saarthal(mage's quest)</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Kyne's Peace</p>

        <ul>
          <li>Ragnvald</li>
          <li>Ranngeig's Fast</li>
          <li>Shroud Hearth Barrow</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Marked For Death</p>

        <ul>
          <li>Autumnwatch Tower</li>
          <li>Dark Brotherhood Sanctuary</li>
          <li>Forsaken Cave</li>
        </ul>
      </div>
    </div>
    <div class="d-flex">
      <div class="shout">
        <p class="fw-bold">Slow Time</p>

        <ul>
          <li>Forsaken Cave</li>
          <li>Korvanjund (civil war)</li>
          <li>Labyrinthian (mage's quest)</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Soul Tear</p>

        <ul>
          <li>Durnehviir</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Storm Call</p>

        <ul>
          <li>Forelhost</li>
          <li>High Gate Ruins</li>
          <li>Skuldafn (main quest)</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Summon Durnehviir</p>

        <ul>
          <li>Soul Cairn</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Throw Voice</p>

        <ul>
          <li>Shearpoint</li>
        </ul>
      </div>
    </div>
    <div class="d-flex">
      <div class="shout w-50">
        <p class="fw-bold">Unrelenting Force</p>

        <ul>
          <li>Main Quest</li>
        </ul>
      </div>
      <div class="shout w-50">
        <p class="fw-bold">Whirlwind Sprint</p>

        <ul>
          <li>Dead Men's Respite</li>
          <li>Main Quest</li>
          <li>Volskygge</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="priests text-center">
    <h4>Dragon Priest Masks</h4>

    <div class="d-flex">
      <div class="d-flex flex-column">
        <p>Hevnoraak = Valthume</p>
      </div>

      <div class="d-flex flex-column">
        <p>Krosis = Shearpoint</p>
      </div>
    </div>
    <div class="d-flex align-items-center">
      <div class="d-flex flex-column">
        <p>Moroei = Labyrinthian</p>
      </div>

      <div class="flex-column"><p>Nahkriin = Skuldafn, Main Quest</p></div>
    </div>
    <div class="d-flex">
      <div class="d-flex flex-column">
        <p>Otar = Ragnvald</p>
      </div>
      <div class="d-flex flex-column">
        <p>Rahgot = Forelhost</p>
      </div>
    </div>

    <div class="d-flex">
      <div class="d-flex flex-column">
        <p>Vokun = High Gate Ruins</p>
      </div>

      <div class="flex-column">
        <p>Volsung = Volskygge</p>
      </div>
    </div>
    <h4>Dragonborn: Masks</h4>

    <div class="d-flex">
      <div class="flex-column">
        <p>Ahzidal = Kolbjorn Barrow</p>
      </div>

      <div class="flex-column">
        <p>Dulkaan = White Ridge Barrow</p>
      </div>
    </div>

    <p>Zahkriisos = Bloodskal Barrow, in Raven Rock Mine</p>
    <p>Miraak = Main Quest</p>
  </div>
</div>

<style>
  .shout {
    width: 20%;
  }

  .shout p {
    text-align: center;
  }

  .shout ul {
    text-align: center;
    list-style-type: none;
  }

  .priests .flex-column {
    width: 50%;
  }
</style>
