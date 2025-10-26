<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "Elder Scrolls V: Skyrim";
  import Sections from "$lib/sections.svelte";
  import * as components from "$lib/skyrimarr.js";

  import arrows from "$lib/docs/skyrimbats/allarrows.txt";
  import shouts from "$lib/docs/skyrimbats/allshouts.txt";
  import bolts from "$lib/docs/skyrimbats/bolts.txt";
  import crafting from "$lib/docs/skyrimbats/craftingperks.txt";
  import daspect from "$lib/docs/skyrimbats/dragonaspect.txt";
  import dsouls from "$lib/docs/skyrimbats/dsouls.txt";
  import grandgems from "$lib/docs/skyrimbats/grandgem.txt";
  import grandmaster from "$lib/docs/skyrimbats/grandmaster.txt";
  import nightingale from "$lib/docs/skyrimbats/nightingale.txt";
  import robes from "$lib/docs/skyrimbats/robes.txt";
  import ulthealing from "$lib/docs/skyrimbats/ulthealing.txt";

  // const sections = [
  //   {
  //     name: "console",
  //     link: "#console",
  //   },

  //   {
  //     name: "bat",
  //     link: "#bat",
  //   },

  //   {
  //     name: "mods",
  //     link: "#mods",
  //   },

  //   {
  //     name: "guides",
  //     link: "#guides",
  //   },
  // ];

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

<!-- <Sections {sections} /> -->

<div id="console" class="console">
  <h2>console commands</h2>

  <table
    class="table table-borderless table-dark table-striped table-responsive"
  >
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
  <a href="#top" class="skiplink">Top</a>
</div>

<div id="bat" class="bat">
  <h2>bat files</h2>
  <p class="fw-bold">What are they?</p>
  <p>
    Bat files are .txt files containing console commands and placed in the games
    root folder. Bringing up the console in game and using the input bat
    (filename) will execute the console commands in that .txt file.
  </p>

  <div class="bat-files d-flex justify-content-center">
    <div class="flex-column">
      <p class="fw-bold">allarrows.txt</p>
      <a href={arrows} download>download</a>
    </div>
    <div class="flex-column">
      <p class="fw-bold">allshouts.txt</p>
      <a href={shouts} download>download</a>
    </div>
    <div class="flex-column">
      <p class="fw-bold">bolts.txt</p>
      <a href={bolts} download>download</a>
    </div>
    <div class="flex-column">
      <p class="fw-bold">craftingperks.txt</p>
      <a href={crafting} download>download</a>
    </div>
    <div class="flex-column">
      <p class="fw-bold">dragonaspect.txt</p>
      <a href={daspect} download>download</a>
    </div>
    <div class="flex-column">
      <p class="fw-bold">dsouls.txt</p>
      <a href={dsouls} download>download</a>
    </div>
    <div class="flex-column">
      <p class="fw-bold">grandgem.txt</p>
      <a href={grandgems} download>download</a>
    </div>
    <div class="flex-column">
      <p class="fw-bold">grandmaster.txt</p>
      <a href={grandmaster} download>download</a>
    </div>
    <div class="flex-column">
      <p class="fw-bold">nightingale.txt</p>
      <a href={nightingale} download>download</a>
    </div>
    <div class="flex-column">
      <p class="fw-bold">robes.txt</p>
      <a href={robes} download>download</a>
    </div>
    <div class="flex-column">
      <p class="fw-bold">ulthealing.txt</p>
      <a href={ulthealing} download>download</a>
    </div>
  </div>

  <a href="#top" class="skiplink">Top</a>
</div>



<div id="guides" class="guides">
  <h2>guides</h2>

  <div class="guide-sections">
    <p class="fw-bold text-decoration-underline">Sections</p>
    <ul class="skip">
      <li><a href="#goldbrand">goldbrand</a></li>
      <li><a href="#recipes">recipes</a></li>
      <li><a href="#shouts">dragon shouts</a></li>
      <li><a href="#masks">dragon priest masks</a></li>
    </ul>
  </div>

  <div class="goldbrand" id="goldbrand">
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

  <div id="recipes">
    <h4>potion recipes</h4>
    <div class="d-flex">
      <div>
        <h5>healing</h5>
        <ul>
          <li>wheat</li>
          <li>blue mountain flower</li>
          <li>blisterwort</li>
          <li>butterfly wing</li>
          <li>blue dartwing</li>
          <li>imp stool</li>
          <li>charred skeever hide</li>
          <li>rock warbler egg</li>
          <li>swamp fungal pod</li>
          <li>eye of saber cat</li>
          <li>daedra heart</li>
          <li>ash hopper jelly</li>
          <li>felsaad tern feathers</li>
        </ul>
      </div>
      <div>
        <h5>magicka</h5>
        <ul>
          <li>briar heart</li>
          <li>creep cluster</li>
          <li>dwarven oil</li>
          <li>ectoplasm</li>
          <li>elves ear</li>
          <li>fire salts</li>
          <li>frost salts</li>
          <li>giant lichen</li>
        </ul>
      </div>
      <div>
        <h5>cure disease</h5>
        <ul>
          <li>charred skeever hide</li>
          <li>hawk feathers</li>
          <li>mudcrab chitin</li>
          <li>vampire dust</li>
        </ul>
      </div>
    </div>
    <div class="d-flex">
      <div>
        <h5>foritfy one-handed</h5>
        <ul>
          <li>bear claws</li>
          <li>canis root</li>
          <li>hanging moss</li>
          <li>hawk feathers</li>
          <li>rock warbler egg</li>
          <li>small pearl</li>
        </ul>
      </div>
      <div>
        <h5>fortify destruction</h5>
        <ul>
          <li>ash creep cluster</li>
          <li>beehive husk</li>
          <li>ectoplasm</li>
          <li>glow dust</li>
          <li>glowing mushroom</li>
          <li>nightshade</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="shouts" id="shouts">
    <h4>Dragon Shouts</h4>

    <div class=" d-flex">
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
    </div>

    <div class="d-flex">
      <div class="shout">
        <p class="fw-bold">Bend Will</p>
        <ul>
          <li>Dragonborn- Main Quest</li>
        </ul>
      </div>
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
    </div>

    <div class="d-flex">
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
      <div class="shout">
        <p class="fw-bold">Dismay</p>

        <ul>
          <li><a href={components.crone}>Dead Crone Rock</a></li>
          <li><a href={components.tongue}>Lost Tongue Overlook</a></li>
          <li>Labyrinthian (Mage's quest)</li>
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
    </div>
    <div class="d-flex">
      <div class="shout">
        <p class="fw-bold">Dragonrend</p>

        <ul>
          <li>Main Quest</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Drain Vitality</p>

        <ul>
          <li><a href={components.arcwind}>Arcwind Point</a></li>
          <li>Dawnguard - Main Quest</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Elemental Fury</p>

        <ul>
          <li><a href={components.dragontooth}>Dragontooth Crater</a></li>
          <li><a href={components.shriekwind}>Shriekwind Bastion</a></li>
          <li>Statue of Meridia</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Fire Breath</p>

        <ul>
          <li>Dustman's Cairn (Companion's Quest)</li>
          <li><a href={components.sunderstone}>Sunderstone Gorge</a></li>
          <li>Main Quest</li>
        </ul>
      </div>
    </div>
    <div class="d-flex">
      <div class="shout">
        <p class="fw-bold">Frost Breath</p>

        <ul>
          <li><a href={components.bone}>Bonestrewn Crest</a></li>
          <li><a href={components.folg}>Folgunthur</a></li>
          <li><a href={components.skyborn}>Skyborn Altar</a></li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Ice Form</p>

        <ul>
          <li><a href={components.frostmere}>Frostmere Crypt</a></li>
          <li><a href={components.anthor}>Mount Anthor</a></li>
          <li>Saarthal(mage's quest)</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Kyne's Peace</p>

        <ul>
          <li><a href={components.rag}>Ragnvald</a></li>
          <li><a href={components.rann}>Rannveig's Fast</a></li>
          <li><a href={components.shroud}>Shroud Hearth Barrow</a></li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Marked For Death</p>

        <ul>
          <li><a href={components.autm}>Autumnwatch Tower</a></li>
          <li>Dark Brotherhood Sanctuary</li>
          <li><a href={components.forsaken}>Forsaken Cave</a></li>
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
          <li><a href={components.forel}>Forelhost</a></li>
          <li><a href={components.hgate}>High Gate Ruins</a></li>
          <li>Skuldafn (main quest)</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Summon Durnehviir</p>

        <ul>
          <li>Soul Cairn</li>
        </ul>
      </div>
    </div>
    <div class="d-flex">
      <div class="shout">
        <p class="fw-bold">Throw Voice</p>

        <ul>
          <li>Shearpoint</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Unrelenting Force</p>

        <ul>
          <li>Main Quest</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Whirlwind Sprint</p>

        <ul>
          <li>Dead Men's Respite</li>
          <li>Main Quest</li>
          <li>Volskygge</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="priests text-center" id="masks">
    <h4>Dragon Priest Masks</h4>

    <div class="d-flex">
      <div class="d-flex flex-column">
        <p>Hevnoraak = Valthume</p>
        <img src={components.valthume} alt="mask" />
      </div>

      <div class="d-flex flex-column">
        <p>Krosis = Shearpoint</p>
        <img src={components.shearpoint} alt="mask" />
      </div>
    </div>
    <div class="d-flex align-items-center">
      <div class="d-flex flex-column">
        <p>Moroei = Labyrinthian</p>
        <img src={components.lab} alt="mask" />
      </div>

      <div class="flex-column"><p>Nahkriin = Skuldafn, Main Quest</p></div>
    </div>
    <div class="d-flex">
      <div class="d-flex flex-column">
        <p>Otar = Ragnvald</p>
        <img src={components.rag} alt="mask" />
      </div>
      <div class="d-flex flex-column">
        <p>Rahgot = Forelhost</p>
        <img src={components.forel} alt="mask" />
      </div>
    </div>

    <div class="d-flex">
      <div class="d-flex flex-column">
        <p>Vokun = High Gate Ruins</p>
        <img src={components.hgate} alt="mask" />
      </div>

      <div class="flex-column">
        <p>Volsung = Volskygge</p>
        <img src={components.vol} alt="mask" />
      </div>
    </div>
    <h4>Dragonborn: Masks</h4>

    <div class="d-flex">
      <div class="flex-column">
        <p>Ahzidal = Kolbjorn Barrow</p>
        <img src={components.kol} alt="mask" />
      </div>

      <div class="flex-column">
        <p>Dulkaan = White Ridge Barrow</p>
        <img src={components.wridge} alt="mask" />
      </div>
    </div>

    <p>Zahkriisos = Bloodskal Barrow, in Raven Rock Mine</p>
    <p>Miraak = Main Quest</p>
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<style>
  .shout {
    width: 20%;
    background-color: white;
    margin: 10px;
    border-radius: 15px;
    height: 200px;
    border-top: 15px solid black;
    border-bottom: 15px double black;
  }

  #recipes .d-flex {
    justify-content: center;
  }

  .shout p {
    text-align: center;
  }

  .shout ul {
    text-align: center;
    list-style-type: none;
    font-size: 15px;
  }

  .priests .flex-column {
    width: 50%;
    padding: 30px;
  }

  .priests img {
    width: 100%;
    height: auto;
  }

  .bat-files div {
    width: 200px;
    text-align: center;
    padding: 10px;
    background-color: white;
    margin: 5px;
    border-radius: 15px;
    border-top: 15px solid black;
    border-bottom: 15px double black;
  }

  table {
    table-layout: fixed;
  }

  table td:first-child {
    text-transform: capitalize;
  }

  img {
    margin-bottom: 0;
  }

  .div div {
    background-color: white;
    margin: 5px;
    border-radius: 15px;
    height: 200px;
    width: 20%;
    border-top: 55px solid black;
    border-bottom: 15px double black;
  }

  @media screen and (max-width: 600px) {
    .priests div,
    .shouts div,
    .bat-files div {
      width: 100% !important;
    }

    .shout {
      height: 250px;
    }

    .div div {
      width: 100%;
    }
  }
</style>
