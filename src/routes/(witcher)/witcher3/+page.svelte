<script>
  import { pageTitle } from "$lib/stores.js";
  pageTitle.set("Witcher 3: Wild Hunt");
  import Sections from "$lib/sections.svelte";
  import * as pop from "$lib/witcher3.js";

  // const sections = [
  //   {
  //     name: "console",
  //     link: "#console",
  //   },

  //   {
  //     name: "guides",
  //     link: "#guides",
  //   },
  // ];

  const commands = [
    {
      name: "god mode",
      input: "god",
      desc: "take no damage",
    },

    {
      name: "money",
      input: "addmoney(amount)",
      desc: "give money",
    },

    {
      name: "heal me",
      input: "healme",
      desc: "restore health",
    },

    {
      name: "shave",
      input: "shave",
      desc: "remove beard",
    },

    {
      name: "skill points",
      input: "addskillpoints(amount)",
      desc: "give skill points",
    },

    {
      name: "win/lose Gwent game",
      input: "winGwint(true/false)",
      desc: "instantly win or lose current Gwent game.",
    },

    {
      name: "Gwent game",
      input: "secretgwint",
      desc: "start a Gwent game.",
    },

    {
      name: "Triss card",
      input: "additem('gwint_card_triss')",
      desc: "give Triss Gwent card.",
    },

    {
      name: "Avallach card",
      input: "additem('gwint_card_avallach')",
      desc: "give Avallach Gwent card.",
    },

    {
      name: "Master Weapon Kit",
      input: 'additem("weapon_repair_kit_3", #)',
      desc: "Master weapon repair kit",
    },

    {
      name: "Master Armor Kit",
      input: 'additem("armor_repair_kit_3", #)',
      desc: "Master weapon repair kit",
    },

    {
      name: "Black Dye",
      input: 'additem("Dye Black")',
      desc: "armor dye",
    },

    {
      name: "Dwarven Spirit",
      input: 'additem("Dwarven spirit")',
      desc: "alchemy",
    },

    {
      name: "White Gull",
      input: 'additem("White Gull 1")',
      desc: "alchemy",
    },
  ];
</script>

<!-- <Sections {sections} /> -->

<div id="console" class="console">
  <h2>console commands</h2>
  <h4>How to Enable</h4>
  <h5>Method 1:</h5>
  <ol>
    <li>Open The Witcher 3/bin/config/base</li>
    <li>Open general.ini</li>
    <li>add DBGConsoleOn=true</li>
  </ol>

  <h5>Method 2:</h5>
  <p>Install a mod.</p>

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

<div id="guides" class="guides">
  <h2>guides</h2>
  <div class="guide-sections">
    <p class="fw-bold text-decoration-underline">Sections</p>
    <ul class="skip">
      <li><a href="#power">places of power</a></li>
    </ul>
  </div>

  <div id="power">
    <h4>places of power</h4>

    <div>
      <p class="fw-bold">white orchard</p>
      <img src={pop.orchard} alt="power" />
    </div>
    <div>
      <p class="fw-bold">velen</p>
      <img src={pop.velen} alt="power" />
    </div>
    
    <div>
      <p class="fw-bold">novigrad</p>
      <img src={pop.novigrad} alt="power" />
    </div>
    <div>
      <p class="fw-bold">skellige</p>
      <img src={pop.skellige1} alt="power" />
      <img src={pop.skellige2} alt="power" />
      <img src={pop.skellige3} alt="power" />
      <img src={pop.skellige4} alt="power" />
      <img src={pop.sunstone} alt="power" />
    </div>
    <div>
      <p class="fw-bold">kaer morhen</p>
      <img src={pop.kaer} alt="power" />
    </div>
    <div>
      <p class="fw-bold">toussaint</p>
      <img src={pop.toussaint} alt="power" />
    </div>
  </div>

  <a href="#top" class="skiplink">Top</a>
</div>

<style>
  #power .fw-bold {
    font-size: 20px;
    text-transform: capitalize;
  }
</style>
