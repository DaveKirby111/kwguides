<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "Mass Effect";
  import Sections from "$lib/sections.svelte";

  // const sections = [
  //   {
  //     name: "mods",
  //     link: "#mods",
  //   },

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

<!-- <Sections {sections} /> -->

<div id="console" class="console">
  <h2>console commands</h2>

  <table
    class="table table-borderless table-dark table-striped table-responsive text-capitalize"
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

  <div class="guide-sections">
    <p class="fw-bold text-decoration-underline">Sections</p>
    <ul class="skip">
      <li><a href="#trophies">trophies</a></li>
      <li><a href="#assignments">assignments</a></li>
      <li><a href="#peak15">peak 15</a></li>
    </ul>
  </div>

  <div id="trophies">
    <h4>trophies</h4>
    <h5>100% completion</h5>
    <div class="d-flex">
      <div>
        <ul>
          <li>n7 elite</li>
          <p>ME1: Acquire all trophies</p>
          <li>medal of honor</li>
          <p>ME1: Complete the game on any difficulty</p>
          <li>medal of heroism</li>
          <p>ME1: Complete Feros</p>
          <li>distinguished service medal</li>
          <p>ME1: Complete Eden Prime</p>
          <li>council legion of merit</li>
          <p>ME1: Complete Virmire</p>
          <li>Honorarium of Corporate Service</li>
          <p>ME1: Complete Noveria</p>
          <li>lift mastery</li>
          <p>ME1: Use biotic Lift 25 times</p>
          <li>throw mastery</li>
          <p>ME1: Use biotic Throw 25 times</p>
          <li>warp mastery</li>
          <p>ME1: Use biotic Warp 25 times</p>
          <li>singularity mastery</li>
          <p>ME1: Use biotic Singularity 25 times</p>
        </ul>
      </div>
      <div>
        <ul>
          <li>barrier mastery</li>
          <p>ME1: Use biotic Barrier 25 times</p>
          <li>stasis mastery</li>
          <p>ME1: Use biotic Stasis 25 times</p>
          <li>damping specialist</li>
          <p>ME1: Use Damping Field 25 times</p>
          <li>AI hacking specialist</li>
          <p>ME1: Use AI Hacking 25 times</p>
          <li>electronics specialist</li>
          <p>ME1: Use Shield Overload 25 times</p>
          <li>sabotage specialist</li>
          <p>ME1: Use Sabotage 25 times</p>
          <li>first aid specialist</li>
          <p>ME1: Use medi-gel 50 times</p>
          <li>neural shock specialist</li>
          <p>ME1: Use Neural Shock 25 times</p>
          <li>Meritorious Service Medal</li>
          <p>ME1: Complete Ilos</p>
          <li>archivist</li>
          <p>ME1: Find all primary Alien: codex entries</p>
        </ul>
      </div>
      <div>
        <ul>
          <li>completionist</li>
          <p>ME1: Complete the majority of the game</p>
          <li>Medal of Exploration I</li>
          <p>ME1: Land on an uncharted world</p>
          <li>Medal of Exploration II</li>
          <p>ME1: Land on 4 uncharted worlds</p>
          <li>Medal of Exploration III</li>
          <p>ME1: Land on 8 uncharted worlds</p>
          <li>soldier ally</li>
          <p>ME1: Complete 5 missions with the Alliance soldier squad member</p>
          <li>sentinel ally</li>
          <p>ME1: Complete 5 missions with the Alliance sentinel squad member</p>
          <li>krogan ally</li>
          <p>ME1: Complete 5 missions with the krogan squad member</p>
          <li>turian ally</li>
          <p>ME1: Complete 5 missions with the turian squad member</p>
          <li>quarian ally</li>
          <p>ME1: Complete 5 missions with the quarian squad member</p>
          <li>asari ally</li>
          <p>ME1: Complete 5 missions with the asari squad member</p>
        </ul>
      </div>
      <div>
        <ul>
          <li>principled</li>
          <p>ME1: Accumulate 75% of total possible Paragon or Renegade points</p>
          <li>spectre inductee</li>
          <p>ME1: Become a Spectre</p>
          <li>charismatic</li>
          <p>ME1: Use Charm or Intimidate to resolve an impossible situation</p>
          <li>search and rescue</li>
          <p>ME1: Locate Dr. T'soni in the Artemis Tau cluster</p>
          <li>colonial savior</li>
          <p>ME1: Complete the Bring Down the Sky mission.</p>
        </ul>
      </div>
    </div>
  </div>

  <div class="assignments" id="assignments">
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

  <div class="peak15" id="peak15">
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

  .div div {
    background-color: white;
    margin: 5px;
    border-radius: 15px;
    height: 200px;
    width: 20%;
    border-top: 55px solid black;
    border-bottom: 15px double black;
  }

  ul li {
      text-transform: capitalize;
    }

    ul p {
      text-transform: capitalize;
      font-size: 12px;
    }

  @media screen and (max-width: 600px) {
    .div div {
      width: 100%;
    }

    .div {
      width: 100%;
      padding: 5px;
    }
  }
</style>
