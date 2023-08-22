<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "mass effect 3";
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

<div class="console" id="console">
  <h2>console commands</h2>
</div>

<div id="guides" class="guides">
  <h2>guides</h2>

  <div class="standoff">
    <h4>priority: citadel II - standoff</h4>

    <table class="table table-bordered table-responsive">
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

  <div class="peace">
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

  <div class="endings">
    <h4>Endings</h4>

    <h5>Legendary Edition</h5>
    <table class="table table-bordered table-responsive mb-5">
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
    <table class="table table-bordered table-responsive">
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
</div>
