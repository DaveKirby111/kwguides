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
</script>

<Sections {sections} />

<div id="mods" class="mods">
  <h2>mods</h2>
</div>

<div id="console" class="console">
  <h2>console commands</h2>
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
    <h3>Peak 15 Puzzles</h3>
    <h5>Memory Core</h5>
    <div class="core">
      <p>
        Core 1 -> 2 | Core 1 -> 3 | Core 2 -> 3 | Core 1 -> 2 | Core 3 -> 1 |
        Core 3 -> 2 | Core 1 -> 2 | Core 1 -> 3 | Core 2 -> 3 | Core 2 -> 1 |
        Core 3 -> 1 | Core 2 -> 3 | Core 1 -> 2 | Core 1 -> 3 | Core 2 -> 3
      </p>
    </div>
  </div>
</div>
