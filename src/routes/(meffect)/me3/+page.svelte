<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "Mass Effect 3";
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
      <li><a href="#standoff">standoff</a></li>
      <li><a href="#rannoch">rannoch</a></li>
      <li><a href="#endings">endings</a></li>
    </ul>
  </div>

  <div id="trophies">
    <h4>trophies</h4>
    <h5>100% completion</h5>
    <div class="d-flex">
      <div>
        <ul>
          <li>n7 elite</li>
          <p>ME3: Acquire all trophies</p>
          <li>driven</li>
          <p>ME3: Return to active duty.</p>
          <li>bringer of war</li>
          <p>ME3: Chase down an assassin.</p>
          <li>mobilizer</li>
          <p>ME3: Bring a veteran officer aboard.</p>
          <li>world shaker</li>
          <p>ME3: Destroy an Atlas dropped from orbit.</p>
          <li>pathfinder</li>
          <p>ME3: Explore a lost city.</p>
          <li>tunnel rat</li>
          <p>ME3: Survive the swarm.</p>
          <li>party crasher</li>
          <p>ME3: Sabotage a dreadnought.</p>
          <li>hard target</li>
          <p>ME3: Call down an orbital strike.</p>
          <li>saboteur</li>
          <p>ME3: Disable a group of fighter squadrons.</p>
          <li>arbiter</li>
          <p>ME3: Win a political stand-off.</p>
          <li>last witness</li>
          <p>ME3: Extract ancient technology.</p>
          <li>executioner</li>
          <p>ME3: Defeat an old adversary.</p>
          <li>well connected</li>
          <p>ME3: Send a warning across the galaxy.</p>
          <li>fact finder</li>
          <p>ME3: Discover an enemy's monstrous origin.</p>
          <li>liberator</li>
          <p>ME3: Stop a Cerberus kidnapping.</p>
          <li>problem solver</li>
          <p>ME3: Evacuate a scientific facility.</p>
          <li>patriot</li>
          <p>ME3: Make the final assault.</p>
          <li>legend</li>
          <p>ME3: Mission accomplished.</p>
          <li>shopaholic</li>
          <p>ME3: Visit a store on the Citadel.</p>
        </ul>
      </div>
      <div>
        <ul>
          <li>master and commabder</li>
          <p>ME3: Deliver most of the War assets to the final conflict.</p>
          <li>lost and found</li>
          <p>ME3: Dispatch 10 probes to retrieve people or resources in Reaper territory.</p>
          <li>a personal touch</li>
          <p>ME3: Modify a weapon.</p>
          <li>combined arms</li>
          <p>ME3: Perform any combination of 50 biotic combos or tech bursts.</p>
          <li>focused</li>
          <p>ME3: Evolve any of your powers to rank 6.</p>
          <li>untouchable</li>
          <p>ME3: Escape a Reaper in the galaxy map.</p>
          <li>shield breaker</li>
          <p>ME3: Overload the shields of 100 enemies.</p>
          <li>sky high</li>
          <p>ME3: Lift 100 enemies off the ground with powers.</p>
          <li>pyromaniac</li>
          <p>ME3: Set 100 enemies on fire with powers.</p>
          <li>eye of the hurricane</li>
          <p>ME3: Kill a brute while it's charging you.</p>
          <li>mail slot</li>
          <p>ME3: Kill 10 guardians with headshots from the front while their shields are raised.</p>
          <li>hijacker</li>
          <p>ME3: Hijack an Atlas mech.</p>
          <li>giant killer</li>
          <p>ME3: Defeat a harvester.</p>
          <li>always prepared</li>
          <p>ME3: Obtain two non-customizable suits of armor.</p>
          <li>gunsmith</li>
          <p>ME3: Upgrade any weapon to level 10.</p>
          <li>under pressure</li>
          <p>ME3: Uncover an ancient secret.</p>
          <li>savior</li>
          <p>ME3: Free Omega from Cerberus Occupation.</p>
          <li>last resort</li>
          <p>ME3: Stop an out-of-control scheme before it's too late.</p>
          <li>the one and only</li>
          <p>ME3: Defeat a group of Spectre-level opponents on Normal, Hardcore, or Insanity.</p>
        </ul>
      </div>
    </div>
  </div>

  <div class="standoff" id="standoff">
    <h4>priority: citadel II - standoff</h4>

    <table
      class="table table-dark table-striped table-bordered table-responsive"
    >
      <thead>
        <tr>
          <th>Factor</th>
          <th>Yes</th>
          <th>No</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Romanced Ashley/Kaidan</td>
          <td>+2</td>
          <td>+0</td>
        </tr>
        <tr>
          <td> * Cheated on them in ME2 *</td>
          <td>-1</td>
          <td>+0</td>
        </tr>
        <tr>
          <td>Saved Council</td>
          <td>+1</td>
          <td>-1</td>
        </tr>
        <tr>
          <td
            >Kept Kirrahe or Thane alive (otherwise Udina will produce a
            fabricated video of Shepard assassinating the salarian Councilor)</td
          >
          <td>+0</td>
          <td>-2</td>
        </tr>
        <tr>
          <td>Shepard was kind to Ashley/Kaidan during Priority: Mars</td>
          <td>+1</td>
          <td>-1</td>
        </tr>
        <tr>
          <td>Visited Ash/Kaidan in hospital once (when awake)</td>
          <td>+2</td>
          <td>+0</td>
        </tr>
        <tr>
          <td> * Admitted and/or apologized for cheating on Ashley/Kaidan *</td>
          <td>+0</td>
          <td>-1</td>
        </tr>
        <tr>
          <td>Visited them a second time</td>
          <td>+1</td>
          <td>+0</td>
        </tr>
        <tr>
          <td>Lowered weapon during standoff</td>
          <td>+1</td>
          <td>+0</td>
        </tr>
      </tbody>
    </table>

    <p class="fw-bold">Final trust level</p>
    <p>-1 or below = They can not be talked down</p>
    <p>0-3 = Reputation check</p>
    <p>4 or higher = They side with Shepard</p>
  </div>

  <div class="peace" id="rannoch">
    <h4>Rannoch: Geth/Quarian Peace</h4>

    <p>You need 5 to 7 points to broker peace.</p>

    <p class="fw-bold">ME2:</p>
    <ul>
      <li>Rewrote Heretics = 0 points</li>
      <li>Destroyed Heretice = 2 points</li>
      <li>Tali is NOT exiled = 2 points</li>
      <li>Tali exiled = 0 points</li>
      <li>Resolved Tali/Legion conflict (paragon/renegade) = 1 point</li>
    </ul>
    <p class="fw-bold">ME3:</p>
    <ul>
      <li>Save Admiril = 1 point</li>
      <li>Complete Legion's mission = 1 point</li>
      <li>Destroy Geth squadron = 1 point</li>
    </ul>
  </div>

  <div class="endings" id="endings">
    <h4>Endings</h4>

    <h5>Legendary Edition</h5>
    <table
      class="table table-dark table-striped table-bordered table-responsive mb-5"
    >
      <thead>
        <tr>
          <th>War Assets</th>
          <th>Red</th>
          <th>Blue</th>
          <th>Green</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>0-1599</td>
          <td
            >Yes if Collector Base destroyed. Huge galaxy damage, kills AI and
            all on Earth. No Normandy survivors.</td
          >
          <td
            >Yes if Collector Base destroyed. Huge galaxy damage, kills AI and
            all on Earth. No Normandy survivors.</td
          >
          <td rowspan="4">This ending is not available at this EMS level.</td>
        </tr>
        <tr>
          <td>1600-2099</td>
          <td
            >Large galaxy damage, AI killed. Joker and two favored squadmates
            exit Normandy (sans EDI).</td
          >
          <td
            >Large galaxy damage, Joker and two favored squadmates exit
            Normandy.</td
          >
        </tr>
        <tr>
          <td>2100-2599</td>
          <td
            >No galaxy damage if Collector Base destroyed, minor if it was
            spared. Kills AI, Joker and two favored squadmates exit Normandy
            (sans EDI).</td
          >
          <td
            >No galaxy damage if Collector Base spared, minor if it was
            destroyed. Joker and two favored squadmates exit Normandy.</td
          >
        </tr>
        <tr>
          <td>2600-3099</td>
          <td rowspan="2"
            >No galaxy damage, kills AI. Joker and two favored squadmates exit
            Normandy (sans EDI).</td
          >
          <td rowspan="3"
            >No galaxy damage. Joker and two favored squadmates exit Normandy.</td
          >
        </tr>
        <tr>
          <td>3100-3699</td>
          <td rowspan="2"
            >No galaxy damage, Joker, EDI and favored squadmate exit Normandy.</td
          >
        </tr>
        <tr>
          <td>3700+</td>
          <td
            >No galaxy damage, kills AI. Joker and two favored squadmates exit
            Normandy (sans EDI). Shepard lives.</td
          >
        </tr>
      </tbody>
    </table>

    <h5>OG ME3 (with Extended Cut)</h5>
    <table
      class="table table-dark table-striped table-bordered table-responsive"
    >
      <thead>
        <tr>
          <th>War Assets</th>
          <th>Red</th>
          <th>Blue</th>
          <th>Green</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>0-1749</td>
          <td
            >Yes if Collector Base destroyed. Huge galaxy damage, kills AI and
            all on Earth. No Normandy survivors.</td
          >
          <td
            >Yes if Collector Base spared. Huge galaxy damage, Joker and two
            favored squadmates exit Normandy.</td
          >
          <td rowspan="4">This ending is not available at this EMS level.</td>
        </tr>
        <tr>
          <td>1750-2349</td>
          <td
            >Large galaxy damage, AI killed. Joker and two favored squadmates
            exit Normandy (sans EDI).</td
          >
          <td
            >Large galaxy damage, Joker and two favored squadmates exit
            Normandy.</td
          >
        </tr>
        <tr>
          <td>2350-2649</td>
          <td
            >No galaxy damage if Collector Base destroyed, minor if it was
            spared. Kills AI, Joker and two favored squadmates exit Normandy
            (sans EDI).</td
          >
          <td
            >No galaxy damage if Collector Base spared, minor if it was
            destroyed. Joker and two favored squadmates exit Normandy.</td
          >
        </tr>
        <tr>
          <td>2650-2799</td>
          <td rowspan="2"
            >No galaxy damage, kills AI. Joker and two favored squadmates exit
            Normandy (sans EDI).</td
          >
          <td rowspan="3"
            >No galaxy damage. Joker and two favored squadmates exit Normandy.</td
          >
        </tr>
        <tr>
          <td>2800-3099</td>
          <td rowspan="2"
            >No galaxy damage, Joker, EDI and favored squadmate exit Normandy.</td
          >
        </tr>
        <tr>
          <td>3100+</td>
          <td
            >No galaxy damage, kills AI. Joker and two favored squadmates exit
            Normandy (sans EDI). Shepard lives if Anderson WASN'T executed by
            Illusive Man.</td
          >
        </tr>
      </tbody>
    </table>
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
    .mods div,
    .console,
    .guides div {
      flex-wrap: wrap;
    }

    .div div {
      width: 100%;
    }
  }
</style>
