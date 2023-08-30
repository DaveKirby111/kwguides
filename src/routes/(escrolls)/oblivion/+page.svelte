<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "elder scrolls IV: oblivion";
  import Sections from "$lib/sections.svelte";
  import umbra from "$lib/images/oblivion/umbra.webp";
  import goldbrand from "$lib/images/oblivion/goldbrand.webp";
  import bbounding from "$lib/docs/oblivionbats/bbounding.txt";
  import alchemy from "$lib/docs/oblivionbats/alchemy.txt";

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
      name: "builds",
      link: "#builds",
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
      name: "Toggle Collision",
      input: "tcl",
      desc: "move through the world.",
    },

    {
      name: "Money",
      input: "player.additem f (amount)",
      desc: "give the player gold",
    },

    {
      name: "Boots of Bloody Bounding",
      input: "player.additem 348ac 1",
      desc: "level 30+, Fortify Acro 18pts, Fortify blade 18pts",
    },

    {
      name: "Goldbrand",
      input: "player.additem 27105 1",
      desc: "fire damage 22 pts",
    },

    {
      name: "Elixir of Exploration (grand)",
      input: "player.additem 4e93a amount",
      desc: "night-eye 300 sec, fortify health and fatigue 20 pts 300sec, fortify blade, blunt, dest, rest, sec, sneak 10pts 300sec.",
    },

    {
      name: "Potion of Cure Disease",
      input: "player.additem 920e amount",
      desc: "cure disease",
    },

    {
      name: "Potion of Nighteye (strong)",
      input: "player.additem 98482 amount",
      desc: "night-eye 90 sec.",
    },

    {
      name: "Potion of Healing (strong)",
      input: "player.additem 9311 amount",
      desc: "restore health 50pts 60 sec.",
    },
  ];
</script>

<Sections {sections} />

<div id="console" class="console">
  <h2>console commands</h2>

  <table class="table table-borderless table-striped table-responsive">
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
    (filename.txt) will execute the console commands in that .txt file.
  </p>

  <div class="bat-files d-flex">
    <div class="flex-column">
      <p class="fw-bold">bbounding.txt</p>
      <a href={bbounding} download>download</a>
    </div>
    <div class="flex-column">
      <p class="fw-bold">alchemy.txt</p>
      <a href={alchemy} download>download</a>
    </div>
  </div>

  <a href="#top" class="skiplink">Top</a>
</div>

<div id="mods" class="mods">
  <h2>mods</h2>

  <div class="d-flex justify-content-center">
    <div class="d-flex flex-column me-5 text-center">
      <p>Oblivion Script Extender</p>
      <p>
        <a
          href="https://github.com/llde/xOBSE/releases/tag/22.6.1"
          target="_blank">Github Page</a
        >
      </p>
    </div>
    <div class="d-flex flex-column me-5 text-center">
      <p>MenuQue - OBSE Plugin</p>
      <p>
        <a href="https://www.nexusmods.com/oblivion/mods/32200?tab=description"
          >Nexus Page</a
        >
      </p>
    </div>
    <div class="d-flex flex-column me-5 text-center">
      <p>All +5 Attribute Modifiers</p>
      <p>
        <a href="https://www.nexusmods.com/oblivion/mods/2691" target="_blank"
          >Nexus Page</a
        >
      </p>
    </div>
    <div class="d-flex flex-column text-center">
      <p>Oblivion XP Update (requires OBSE and MenuQue)</p>
      <p>
        <a
          href="https://www.nexusmods.com/oblivion/mods/51817?tab=description"
          target="_blank">Nexus Page</a
        >
      </p>
    </div>
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<div id="builds" class="builds">
  <h2>builds</h2>

  <div class="witcher">
    <h4>Witcher</h4>
    <h5>Specialization</h5>
    <ul>
      <li>Magic</li>
    </ul>
    <h5>Attributes</h5>
    <ul>
      <li>Willpower</li>
      <li>Endurance</li>
    </ul>
    <h5>Major</h5>
    <ul>
      <li>Blade</li>
      <li>Alchemy</li>
      <li>Alteration</li>
      <li>Block</li>
      <li>Destruction</li>
      <li>Restoration</li>
      <li>Heavy Armor</li>
    </ul>
    <h5>Birthsign</h5>
    <ul>
      <li>Mage: +50 magicka</li>
      <li>Apprentice: +100 magicka, -100% magic resistance</li>
      <li>Atronach: +150 magicka, stunted magicka regen</li>
      <li>Lady: +10 to willpower and endurance</li>
      <li>Warriar: +10 to strength and endurance</li>
    </ul>
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<div id="guides" class="guides">
  <h2>guides</h2>

  <div class="umbra mb-5">
    <h4>umbra</h4>

    <img src={umbra} alt="umbra" />

    <p class="fw-bold">Clavicus Vile's Shrine (quest)</p>

    <ul>
      <li>Level: 20</li>
      <li>Offering: 500 gold</li>
    </ul>

    <p class="fw-bold">Umbra (person)</p>

    <ul>
      <li>Location: Vindasel</li>
      <li>Level: 50</li>
      <li>Health: 394</li>
      <li>Magicka: 172</li>
    </ul>
  </div>

  <div class="goldbrand mb-5">
    <h4>goldbrand</h4>

    <img src={goldbrand} alt="goldb" />

    <p class="fw-bold">Boethiah's Shrine</p>

    <ul>
      <li>Level: 20</li>
      <li>Offering: Deadra Heart</li>
    </ul>
  </div>

  <div class="hatreds-soul">
    <h4>hatred's soul</h4>

    <table class="table table-bordered table-responsive mb-5 w-75 m-auto">
      <thead>
        <tr class="text-center">
          <th>Level</th>
          <th>Weight</th>
          <th>Durability</th>
          <th>Damage</th>
          <th>Enchantment</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>1-4 <br /> 14d65</td>
          <td>12</td>
          <td>300</td>
          <td>15</td>
          <td>Drain Speed 5pts for 10 secs, Fire Damage 5pts</td>
        </tr>
        <tr>
          <td>5-7 <br /> 14d66</td>
          <td>12</td>
          <td>320</td>
          <td>16</td>
          <td>Drain Speed 10pts for 15 secs, Fire Damage 10pts</td>
        </tr>
        <tr>
          <td>8-10 <br /> 14d67</td>
          <td>12</td>
          <td>400</td>
          <td>18</td>
          <td>Drain Speed 15pts for 20 secs, Fire Damage 15pts</td>
        </tr>
        <tr>
          <td>11-14 <br /> 14d68</td>
          <td>12</td>
          <td>500</td>
          <td>20</td>
          <td>Drain Speed 20pts for 20 secs, Fire Damage 20pts</td>
        </tr>
        <tr>
          <td>15-18 <br /> 14d69</td>
          <td>12</td>
          <td>572</td>
          <td>22</td>
          <td>Drain Speed 25pts for 30 secs, Fire Damage 25pts</td>
        </tr>
        <tr>
          <td>19+ <br /> 14d6a</td>
          <td>12</td>
          <td>600</td>
          <td>24</td>
          <td>Drain Speed 30pts for 45 secs, Fire Damage 35pts</td>
        </tr>
      </tbody>
    </table>
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<style>
  img {
    display: block;
    margin: auto;
    margin-bottom: 40px;
  }

  .bat-files div {
    width: 25%;
    text-align: center;
    padding: 10px;
  }

  .bat-files {
    justify-content: center;
  }

  table {
    table-layout: fixed;
  }

  table td:first-child {
    text-transform: capitalize;
  }
</style>
