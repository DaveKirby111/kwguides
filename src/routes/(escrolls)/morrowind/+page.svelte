<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "elder scrolls III: morrowind";
  import Sections from "$lib/sections.svelte";
  import abanabi from "$lib/images/morrowind/Abanabi.png";
  import umbra from "$lib/images/morrowind/umbra.jpg";

  const sections = [
    {
      name: "setup",
      link: "#setup",
    },

    {
      name: "console",
      link: "#console",
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
      desc: "toggle god mode",
    },

    {
      name: "money",
      input: "player->additem gold_001 amount",
      desc: "give gold",
    },

    {
      name: "fill map",
      input: "fillmap",
      desc: "shows all towns on the map",
    },

    {
      name: "reset actors",
      input: "ra",
      desc: "reset the location of every npc",
    },

    {
      name: "unlock",
      input: "unlock",
      desc: "unlocks currently selected lock",
    },

    {
      name: "exquisite amulet",
      input: "player->additem exquisite_amulet_01 1",
      desc: "enchant 120",
    },

    {
      name: "golden saint soul gem",
      input: 'player->additem "golden saint" misc_soulgem_grand 1',
      desc: "filled grand soul gem",
    },
  ];
</script>

<Sections {sections} />

<div id="setup" class="setup">
  <h2>setup</h2>

  <p class="mb-5">
    These are two seperate ways to improve the experience of playing Morrowind
    on PC. I have played the game without any of these installs, with MSE + etc.
    as well as with OpenMW. OpenMW has been the best experience I have had with
    Morrowind on PC. That is simply because due to how old Morrowind is, it's
    engine was not designed for newer hardware and OpenMW is. I have experienced
    zero performance issues.
  </p>
  <div class="OGmorrowind">
    <span>MSE + MCP + MGE</span>
    <p class="mt-3">
      Morrowind Script Extender + Morrowind Code Patch + Morrowind Graphics
      Extender XE
    </p>
    <p class="text-decoration-underline">What is it?</p>
    <p>
      This is a combination of different installs for Morrowind's original
      engine. The code patch is intended to address many of the games bugs as
      well as adding some additional features. MGE improves on the game's
      graphics. The script extender adds new functionality to Morrowind's
      scripting to allow for new features and mods.
    </p>
    <span>Install Process:</span>
    <ol>
      <li>
        Extract MCP to Morrowind directory and run Morrowind Code Patch.exe
      </li>
      <li>Extract MGE XE to Morrowind directory and run MGEXEgui.exe:</li>
      <ul>
        <li>select resolution (1920x1080)</li>
        <li>Menu UI scaling = 1.50</li>
      </ul>
      <li>Extrace MSE to Morrowind directory and run MWSE-Update.exe</li>
    </ol>
    <div class="d-flex justify-content-center">
      <div class="d-flex flex-column me-5">
        <p class="text-center">MSE</p>
        <p>
          <a
            href="https://www.nexusmods.com/morrowind/mods/45468?tab=description"
            target="_blank">Nexus Page</a
          >
        </p>
      </div>
      <div class="d-flex flex-column me-5">
        <p class="text-center">MCP</p>
        <p>
          <a
            href="https://www.nexusmods.com/morrowind/mods/19510?tab=description"
            target="_blank">Nexus Page</a
          >
        </p>
      </div>
      <div class="d-flex flex-column">
        <p class="text-center">MGE</p>
        <p>
          <a
            href="https://www.nexusmods.com/morrowind/mods/41102?tab=description"
            target="_blank">Nexus Page</a
          >
        </p>
      </div>
    </div>
  </div>
  <div class="openmw">
    <span>openMW</span>
    <p class="text-decoration-underline mt-3">What is it?</p>
    <p>
      OpenMW is a new engine for Morrowind designed to work on modern hardware
      without the technical issues of Morrowind's original engine.
    </p>
    <div>
      <p>
        <a href="https://openmw.org/en/" class="me-3" target="_blank"
          >Visit Site</a
        >
      </p>
    </div>
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<div id="console" class="console">
  <h2>console commands</h2>

  <table class="table table-borderless table-striped table-responsive">
    <thead>
      <tr>
        <th>name</th>
        <th>input</th>
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
<div id="mods" class="mods">
  <h2>mods</h2>

  <div class="d-flex justify-content-center">
    <div class="d-flex flex-column me-5 text-center">
      <p>Multiple Teleport Marking</p>
      <p>
        <a
          href="https://www.nexusmods.com/morrowind/mods/44825?tab=description"
          target="_blank">Nexus Page</a
        >
      </p>
    </div>
    <div class="d-flex flex-column text-center">
      <p>Cheat Menu (requires MWSE)</p>
      <p>
        <a href="https://www.nexusmods.com/morrowind/mods/47143" target="_blank"
          >Nexus Page</a
        >
      </p>
    </div>
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<div id="builds" class="builds">
  <h2>builds</h2>

  <div class="witcher w-25">
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
      <li>Long Blade</li>
      <li>Medium Armor</li>
      <li>Desctruction</li>
      <li>Restoration</li>
      <li>Illusion</li>
    </ul>
    <h5>Minor</h5>
    <ul>
      <li>Alchemy</li>
      <li>Enchantment</li>
      <li>Athletics</li>
      <li>Alteration</li>
      <li>Conjuration</li>
    </ul>
    <h5>Birthsign</h5>
    <ul>
      <li>Mage: +50 magicka</li>
      <li>Apprentice: +100 magicka, 50% weakness to magicka</li>
      <li>Atronach: +150 magicka, stunted magicka</li>
      <li>Lover: +25 agility</li>
      <li>Lady: +25 personality and endurance</li>
    </ul>
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<div id="guides" class="guides">
  <h2>guides</h2>

  <div class="chrysamere mb-5">
    <h4>Chrysamere</h4>

    <p>In the cave of Abanabi, south of Sadrith Mora.</p>

    <img src={abanabi} alt="map" />
  </div>

  <div class="umbra mb-5">
    <h4>umbra</h4>

    <p>
      To fight Umbra, you should optimally be a relatively high level,
      preferably above level 20 and with a high number of health points.
    </p>

    <p>
      If you are using a close-up melee weapon, make sure that Umbra doesn’t get
      the chance to react. If possible, keep hitting him. A high weapon skill,
      fatigue and possible Fortify weapon skill, Fortify Attack and/or Fortify
      Strength will help you. The first two will decrease your chance to miss,
      while the third will make your hits more powerful.
    </p>

    <p>
      If you are a ranged fighter. A spell caster or marksman should keep
      his/her distance away from Umbra. If you are faster than him or have the
      Boots of Blinding Speed, then simply blast at him while running away.
    </p>

    <ol>
      <li>
        Have quality/exuisite potions of health with you in case he hits you.
        His hits are painful.
      </li>
      <li>
        Things like armour, shield spell, sanctuary spell, summons, Sujamma,
        powerful weapons etc. can all help you prevail.
      </li>
      <li>
        Make him a stationary target by using Damage Strength, Paralyze, Damage
        Fatigue or Burden. They are sorted in order of effectiveness. Damage
        Strength is the most optimal as it will make him permanently stay where
        he is, so he’s not a danger unless you enter his melee range.
      </li>
    </ol>

    <p class="fw-bold">Quest Giver</p>

    <p>
      Go to the Suran Tradehouse, and ask Ashumanu Eraishah about latest rumors,
      and she will tell you about a dangerous-looking Orc she saw in the hills
      to the east of town. She'll warn you to steer clear, but who are you to
      listen to warnings?
    </p>

    <p class="fw-bold">Finding Umbra</p>

    <p>
      To find him, exit the tradehouse and face the hills. Use a Levitate spell
      or potion to ascend them, or if your Acrobatics skill is high enough you
      could try climbing the pass on foot. There's also a pass around the
      mountains, but it's difficult to find, and a much longer walk. A way to
      make the walk more efficient is to find Umbra after you do the Inanius Egg
      Mine quest, as he is just around the corner from there. You should see
      Umbra surrounded by a wall or pile of rocks.
    </p>

    <p>You can also go around the mountains past the manor.</p>

    <img src={umbra} alt="map" />
  </div>

  <div class="attacks">
    <h4>how to stop dark brotherhood attacks</h4>

    <p>
      Talk to a guard about the Dark Brotherhood attacks and you will be pointed
      to Apelles Matius in Ebonheart. Talk to him and the attacks will stop.
      This is part of the Tribunal dlc.
    </p>
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<style>
  img {
    display: block;
    margin: auto;
  }

  table {
    table-layout: fixed;
  }
</style>
