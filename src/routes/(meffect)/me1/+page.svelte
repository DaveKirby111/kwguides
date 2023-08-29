<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "mass effect";
  import Sections from "$lib/sections.svelte";

  const sections = [
    {
      name: "mods",
      link: "#mods",
    },

    {
      name: "console",
      link: "#console",
    },

    {
      name: "guides",
      link: "#guides",
    },
  ];

  const commands = [
    {
      name: "credits",
      input: "initcredits amount",
      desc: "give credits",
    },

    {
      name: "omni-gel",
      input: "initsalvage",
      desc: "give omni-gel",
    },

    {
      name: "experience",
      input: "givexp amount",
      desc: "give experience points",
    },

    {
      name: "talent points",
      input: "givetalentpoints amount",
      desc: "give talent points",
    },
  ];
</script>

<Sections {sections} />

<div id="mods" class="mods">
  <h2>mods</h2>

  <h4>OG ME 1 mods</h4>
  <div class="d-flex mb-5 justify-content-center">
    <div class="me-5 text-center">
      <p>Trilogy Save Editor for OG and LE</p>
      <p>
        <a
          href="https://www.nexusmods.com/masseffectlegendaryedition/mods/20?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>ME3Tweaks Mod Manager</p>
      <p>
        <a
          href="https://www.nexusmods.com/masseffectlegendaryedition/mods/2?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>Keepers Finders</p>
      <p>
        <a
          href="https://www.nexusmods.com/masseffect/mods/205?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>Galaxy Map Trackers</p>
      <p>
        <a
          href="https://www.nexusmods.com/masseffect/mods/186?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>Mako - Improved Controls Mod</p>
      <p>
        <a
          href="https://www.nexusmods.com/masseffect/mods/59?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
  </div>

  <h4>Legendary Edition Mods</h4>
  <div class="d-flex justify-content-center">
    <div class="me-5 text-center">
      <p>Keepers Finders</p>
      <p>
        <a href="http://" target="_blank" rel="noopener noreferrer"
          >Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>Galaxy Map Trackers</p>
      <p>
        <a
          href="https://www.nexusmods.com/masseffectlegendaryedition/mods/426?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>Breather Helmet for LE1</p>
      <p>
        <a
          href="https://www.nexusmods.com/masseffectlegendaryedition/mods/1843?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>LE1 Community Patch</p>
      <p>
        <a
          href="https://www.nexusmods.com/masseffectlegendaryedition/mods/23?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<div id="console" class="console">
  <h2>console commands</h2>

  <table
    class="table table-borderless table-striped table-responsive text-capitalize"
  >
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

<div id="guides" class="guides">
  <h2>guides</h2>

  <div class="assignments">
    <h4>assignments</h4>
    <h5>citadel</h5>
    <ul>
      <li>Asari Consort</li>
      <li>Doctor Michel</li>
      <li>Homecoming</li>
      <li>Jahleed: Scan Keepers</li>
      <li>Presidium Prophet</li>
      <li>Reporter's Request</li>
      <li>Schells the gambler</li>
      <li>Signal Tracking</li>
      <li>The Fan</li>
      <li>Xeltan's Complain</li>
      <li>Rita's Sister</li>
    </ul>

    <h5>galaxy</h5>
    <ul>
      <li>Hostile Takeover</li>
      <ul>
        <li>Gemini Sigma -> Han -> Mavigon</li>
        <li>Hades Gamma -> Dis -> Klensal</li>
        <li>Horse Head Nebula -> Fortuna -> Amaranthine</li>
      </ul>
      <li>Dead Scientists</li>
      <ul>
        <li>Kepler Verge -> Newton -> Ontarom</li>
      </ul>
      <li>Geth Incursions</li>
      <ul>
        <li>Armstrong Cluster</li>
      </ul>
      <li>ExoGeni Facility</li>
      <ul>
        <li>Maroon Sea -> Vostok -> Nodacrux</li>
      </ul>
      <li>Missing Survey Team</li>
      <ul>
        <li>Hades Gamma -> Antaeus -> Trebin</li>
      </ul>
      <li>Privateers</li>
      <ul>
        <li>Prereq: talk to Garoth on Citadel</li>
        <li>Horse Head Nebula -> Strenuus -> Xawin</li>
      </ul>
      <li>Major Kyle</li>
      <ul>
        <li>Hawking Eta -> Century -> Presop</li>
      </ul>
      <li>Asari Diplomacy</li>
      <ul>
        <li>Artemis Tau -> Macedon -> Sharjila</li>
      </ul>
      <li>Missing Marines</li>
      <ul>
        <li>Artemis Tau -> Sparta -> Edolus</li>
      </ul>
      <li>Cerberus</li>
      <ul>
        <li>Prereq: Missing Marines</li>
        <li>Voyager -> Yangtze -> Binthu</li>
      </ul>
      <li>Hades' Dogs</li>
      <ul>
        <li>Prereq: Missing Marines then Cerberus</li>
        <li>Voyager -> Columbia -> Nepheron</li>
      </ul>
      <li>Colony of the Dead</li>
      <ul>
        <li>Maroon Sea -> Matano -> Chasca</li>
      </ul>
      <li>Espionage Probe</li>
      <ul>
        <li>Voyager -> Amazon</li>
      </ul>
      <li>Depot Sigma-23</li>
      <ul>
        <li>Argos Rho -> Gorgon</li>
      </ul>
      <li>Derelict Freighter</li>
      <ul>
        <li>Maroon Sea -> Caspien</li>
      </ul>
      <li>Distress Call</li>
      <ul>
        <li>Argos Rho -> Hydra -> Metgos</li>
      </ul>

      <li>Hostage</li>
      <ul>
        <li>Hades Gamma -> Farinata -> MSV Ontario</li>
      </ul>
      <li>Listening Post Alpha</li>
      <ul>
        <li>Styx Theta -> Erebus</li>
      </ul>
      <li>Listening Post Theta</li>
      <ul>
        <li>Styx Theta -> Acheron</li>
      </ul>
      <li>Rogue VI</li>
      <ul>
        <li>Prereq: reach level 20</li>
        <li>Local -> Sol -> Luna</li>
      </ul>
      <li>Lost Freighter</li>
      <ul>
        <li>Gemini Sigma -> Ming -> MSV Worthington</li>
      </ul>
      <li>Lost Module</li>
      <ul>
        <li>Attican Beta -> Hercules -> Eletania</li>
      </ul>
    </ul>
  </div>

  <div class="peak15">
    <h4>Peak 15 Puzzles</h4>
    <h5>Memory Core</h5>
    <div class="core">
      <p>
        Core 1 -> 2 | Core 1 -> 3 | Core 2 -> 3 | Core 1 -> 2 | Core 3 -> 1 |
        Core 3 -> 2 | Core 1 -> 2 | Core 1 -> 3 | Core 2 -> 3 | Core 2 -> 1 |
        Core 3 -> 1 | Core 2 -> 3 | Core 1 -> 2 | Core 1 -> 3 | Core 2 -> 3
      </p>
    </div>
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<style>
  table {
    table-layout: fixed;
  }
</style>
