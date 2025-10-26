<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "Mass Effect 2";
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



<div class="console" id="console">
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
      <li><a href="#suicide">suicide mission</a></li>
    </ul>
  </div>

  <div id="trophies">
    <h4>trophies</h4>
    <h5>100% completion</h5>
    <div class="d-flex">
      <div>
        <ul>
          <li>n7 elite</li>
          <p>ME2: Acquire all trophies</p>
          <li>mission accomplished</li>
          <p>ME2: Save humanity from certain annihilation</p>
          <li>missing in action</li>
          <p>ME2: Save your crew from an overwhelming attack</p>
          <li>very elusive</li>
          <p>ME2: Return to active duty</p>
          <li>colony defense</li>
          <p>ME2: Defend a human colony from attack</p>
          <li>ghost ship</li>
          <p>ME2: Complete the investigation of a derelict alien vessel</p>
          <li>suicide mission</li>
          <p>ME2: Use the Omega 4 Relay</p>
          <li>against all odds</li>
          <p>ME2: Survive suicide mission</p>
          <li>no one left behind</li>
          <p>ME2: Keep your team alive through the suicide mission</p>
          <li>friend or foe</li>
          <p>ME2: Obtain geth technology</p>
          <li>the archangel</li>
          <p>ME2: recruit Archangel</p>
          <li>the assassin</li>
          <p>ME2: recruit the Assassin</p>
          <li>the convict</li>
          <p>ME2: recruit the biotic Convict</p>
          <li>the justicar</li>
          <p>ME2: recruit the Justicar</p>
          <li>the krogan</li>
          <p>ME2: recruit the krogan</p>
          <li>the professor</li>
          <p>ME2: recruit the Professor</p>
          <li>the quarian</li>
         <p>ME2: recruit the quarian</p>
          <li>a house divided</li>
          <p>ME2: Hack a geth collective</p>
          <li>battlemaster</li>
          <p>ME2: Gain the loyalty of the krogan</p>
          <li>cat's in the cradle</li>
          <p>ME2: Gain the loyalty of the Assassin</p>
          <li>catharsis</li>
          <p>ME2: Gain the loyalty of the biotic Convict</p>
          <li>doppelganger</li>
          <p>ME2: Help the Justicar resolve her mission</p>
          <li>fade away</li>
          <p>ME2: Gain the loyalty of Archangel</p>
        </ul>
      </div>
      <div>
        <ul>
          <li>ghost of the father</li>
          <p>ME2: Gain the loyalty of the Cerberus Operative</p>
          <li>the cure</li>
          <p>ME2: Gain the loyalty of the Professor</p>
          <li>the prodigal</li>
          <p>ME2: Gain the loyalty of the Cerberus Officer</p>
          <li>treason</li>
          <p>ME2: Gain the loyalty of the quarian</p>
          <li>big game hunter</li>
          <p>ME2: Thresher Maw defeated</p>
          <li>head hunter</li>
          <p>ME2: Perform 30 headshot kills with any weapon on humanoid targets</p>
          <li>incineration specialist</li>
          <p>ME2: Incinerate the armor of 25 enemies</p>
          <li>merciless</li>
          <p>ME2: Make 20 enemies scream as they fall or are set on fire</p>
          <li>overload specialist</li>
          <p>ME2: Disrupt the shields of 25 enemies</p>
          <li>tactician</li>
          <p>ME2: Hit 20 different targets with multiple biotic combos</p>
          <li>warp specialist</li>
          <p>ME2: Warp the barriers of 25 enemies</p>
          <li>agent</li>
          <p>ME2: Complete 5 missions discovered by scanning unexplored worlds</p>
          <li>galactic explorer</li>
          <p>ME2: Visit 100% of the planets in an unexplored cluster</p>
          <li>operative</li>
          <p>ME2: Complete a mission discovered by scanning an unexplored world</p>
          <li>scientist</li>
          <p>ME2: Complete any research project in the Normandy's laboratory</p>
          <li>weapon specialist</li>
          <p>ME2: Fully upgrade a weapon</p>
          <li>scholar</li>
          <p>ME2: Unlock 15 new Mass Effect 2 codex entries</p>
          <li>power full</li>
          <p>ME2: Evolve any power</p>
          <li>revenge!</li>
          <p>ME2: Gain the loyalty of the mercenary</p>
          <li>broke, blind and bedlam</li>
          <p>ME2: Gain the loyalty of the thief</p>
          <li>digital exorcist</li>
          <p>ME2: Successfully shut down the rogue VI</p>
          <li>heart of darkness</li>
          <p>ME2: Confront the Shadow Broker</p>
        </ul>
      </div>
    </div>
  </div>

  <div class="assignments" id="assignments">
    <h4>assignments</h4>
    <h5>Galaxy</h5>
    <ul>
      <li>Endangered Research Station</li>
      <ul>
        <li>Caleston Rift -> Solveig -> Sinmara</li>
      </ul>
      <li>Mining the Canyon</li>
      <ul>
        <li>Caleston Rift -> Talava -> Taitus</li>
      </ul>
      <li>Blood Pack Communication Relay</li>
      <ul>
        <li>Crescent Nebula -> Lusarn -> Tarith</li>
      </ul>
      <li>Captured Mining Facility</li>
      <ul>
        <li>Crescent Nebula -> Zelene -> Helyme</li>
      </ul>
      <li>Wrecked Merchant Freighter</li>
      <ul>
        <li>Eagle Nebula -> Amun -> Neith</li>
      </ul>
      <li>Abandoned Research Station</li>
      <ul>
        <li>Eagle Nebula -> Strabo -> Jarrahe Station</li>
      </ul>
      <li>Quarian Crash Site</li>
      <ul>
        <li>Hades Nexus -> Sheol -> Gei Hinnom</li>
      </ul>
      <li>Eclipse Smuggling Depot</li>
      <ul>
        <li>Hourglass Nebula -> Faryar -> Daratar</li>
      </ul>
      <li>Estevanico</li>
      <ul>
        <li>Hourglass Nebula -> Ploitari -> Zanethu</li>
      </ul>
      <li>Abandoned Mine</li>
      <ul>
        <li>Minos Wasteland -> Fortis -> Aequitas</li>
      </ul>
      <li>MSV Strontium Mule</li>
      <ul>
        <li>Omega Nebula -> Arinlarkan -> MSV Strontium Mule</li>
      </ul>
      <li>Lost Operative</li>
      <ul>
        <li>Omega Nebula -> Fathar -> Lorek</li>
      </ul>
      <li>Anomalous Weather Detected</li>
      <ul>
        <li>Pylos Nebula -> Dirada -> Canalus</li>
      </ul>
      <li>Imminent Ship Crash</li>
      <ul>
        <li>Pylos Nebula -> Nariph -> MSV Broken Arrow</li>
      </ul>
      <li>Archeological Dig Site</li>
      <ul>
        <li>Rosetta Nebula -> Enoch -> Joab</li>
      </ul>
      <li>Blood Pack Base</li>
      <ul>
        <li>Shrike Abyssal -> Xe Cha -> Zada Ban</li>
      </ul>
      <li>Blue Suns Base</li>
      <ul>
        <li>Sigurd's Cradle -> Decoris -> Sanctum</li>
      </ul>
      <li>Javelin Launch</li>
      <ul>
        <li>Sigurd's Cradle -> Skepsis -> Franklin</li>
      </ul>
      <li>Hahne-Kedar Facility</li>
      <ul>
        <li>Titan Nebula -> Haskins -> Capek</li>
      </ul>
    </ul>
  </div>

  <div class="s-mission" id="suicide">
    <h4>suicide mission</h4>

    <h5>normandy upgrades</h5>
    <ul>
      <li>Heavy Ship Armor</li>
      <li>Multicore Shielding</li>
      <li>Thanix Cannon</li>
    </ul>

    <p>
      The following list shows, in order of preference, which crew member will
      die if you haven't upgraded a particular part:
    </p>

    <ul>
      <li>Heavy Ship Armor: Jack</li>
      <li>
        Multicore Shielding: Kasumi, Legion, Tali, Thane, Garrus, Zaeed, Grunt
      </li>
      <li>Thanix Cannon: Thane, Garrus, Zaeed, Grunt, Jack, Samara/Morinth</li>
    </ul>

    <h5>mission choices (assumes team mate is loyal)</h5>
    <p>* Lists most ideal options *</p>

    <p>Tech Specialist: Legion, Tali, Kasumi</p>
    <p>Fire Team pt. 1: Garrus, Jacob, Miranda</p>
    <p>Biotic Specialist: Samara, Jack</p>
    <p>Fire Team pt. 2: Miranda, Garrus, Jacob</p>
    <p>Escort: Mordin, Tali, Kasumi, Jack</p>
    <p>Hold the Line - see below</p>

    <h5>final battle and team left behind</h5>

    <p>
      To get a team that can Hold the Line, this group must average 2 points.
    </p>
    <p>If not loyal, subtract 1 from their point value.</p>

    <ul>
      <li>Grunt, Garrus, Zaeed = 4 points</li>
      <li>Thane, Legion, Samara, Jacob, Miranda = 2 points</li>
      <li>Jack, Tali, Mordin, Kasumi = 1 point</li>
    </ul>

    <p>
      To calculate the average: add up the number of points and divide by the
      number of people.
    </p>

    <p class="fw-bold">Example 1:</p>
    <p>Grunt 4 Zaeed 4 = 8</p>
    <p>Legion 2 Samara 2 Jacob 2 Miranda 2 = 8</p>
    <p>Jack 1 Tali 0 Kasumi 1 = 2</p>
    <p>Total = 18/9 = 2.0 average.</p>

    <p class="fw-bold">Example 2:</p>
    <p>Grunt 4 Zaeed 4 Garrus 4 = 12</p>
    <p>Legion 2 Samara 2 Jacob 2 = 6</p>
    <p>Jack 1 Tali 0 Kasumi 1 = 2</p>
    <p>Total = 20/9 = 2.22 average.</p>

    <p class="fw-bold">Example 3:</p>
    <p>Thane 2 Legion 2 Samara 2 Jacob 2 = 8</p>
    <p>Jack 1 Tali 1 Mordin 1 = 3</p>
    <p>Total= 11/7 = 1.57</p>
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<style>
  h3 {
    text-align: center;
  }

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
  }
</style>
