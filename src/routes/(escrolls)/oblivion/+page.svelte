<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "elder scrolls IV: oblivion";
  import Sections from "$lib/sections.svelte";
  import umbra from "$lib/images/oblivion/umbra.webp";
  import goldbrand from "$lib/images/oblivion/goldbrand.webp";

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

<div id="mods" class="mods" />
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
</div>

<style>
  img {
    display: block;
    margin: auto;
  }
</style>
