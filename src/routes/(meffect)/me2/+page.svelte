<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "mass effect 2";
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

  <div class="assignments">
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

  <div class="s-mission">
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
</div>
