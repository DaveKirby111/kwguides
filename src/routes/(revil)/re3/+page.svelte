<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "Resident Evil 3 Remake";
  import Sections from "$lib/sections.svelte";

  // const sections = [
  //   {
  //     name: "guides",
  //     link: "#guides",
  //   },
  // ];
</script>

<!-- <Sections {sections} /> -->

<div id="guides" class="guides">
  <h2>guides</h2>

  <div class="guide-sections">
    <p class="fw-bold text-decoration-underline">Sections</p>
    <ul class="skip">
      <li><a href="#trophies">trophies</a></li>
      <li><a href="#rank">rank</a></li>
      <li><a href="#route">train station route</a></li>
      <li><a href="#vaccine">lab vaccine</a></li>
      <li><a href="#codes">codes</a></li>
      <li><a href="#dolls">charlie dolls</a></li>
    </ul>
  </div>

  <div id="trophies">
    <h4>trophies</h4>
    <h5>100% completion</h5>
    <div class="d-flex">
      <div>
        <ul>
          <li>so long, RC</li>
          <p>Obtain all trophies.</p>
          <li>fire escape</li>
          <p>Escape from Jill's apartment building.</p>
          <li>somebody to lean on</li>
          <p>Escape from uptown Raccoon City.</p>
          <li>escape from the city</li>
          <p>Make it out of downtown Raccoon City.</p>
          <li>i don't feel so good</li>
          <p>Leave the clock tower plaza.</p>
          <li>dominator</li>
          <p>Complete the game on "Inferno."</p>
          <li>basic chemistry</li>
          <p>craft an item</p>
          <li>gunsmith</li>
          <p>improve a weapon</p>
          <li>get organized</li>
          <p>Expand your inventory.</p>
          <li>nemesis down</li>
          <p>Cause Nemesis to relinquish an item.</p>
          <li>nemesis down?</li>
          <p>Defeat Nemesis on the rooftop.</p>
        </ul>
      </div>
      <div>
        <ul>
          <li>power stones</li>
          <p>Place all jewels in the clock tower monument.</p>
          <li>the carlos express</li>
          <p>Leave R.P.D.</p>
          <li>an unfortunate end</li>
          <p>Defeat zombie Brad.</p>
          <li>jill valentine</li>
          <p>Complete the game with an S rank on "Inferno."</p>
          <li>i need a hero</li>
          <p>Withstand the zombie siege.</p>
          <li>the pursuer</li>
          <p>Follow Nicholai deeper underground.</p>
          <li>electric slide</li>
          <p>Gather all the fuses in the warehouse within 5 minutes.</p>
          <li>nemesis down!?</li>
          <p>Defeat Stage 2 Nemesis.</p>
          <li>nemesis down!!!</li>
          <p>Defeat Stage 3 Nemesis.</p>
          <li>hello, charlie!</li>
          <p>Destroy a Charlie Doll.</p>
          <li>two for one deal</li>
          <p>Defeat two enemies with a single shot.</p>
        </ul>
      </div>
      <div>
        <ul>
          <li>bookworm</li>
          <p>Read all story files.</p>
          <li>goodbye, charlie!</li>
          <p>Destroy all Charlie dolls.</p>
          <li>kendo's armory</li>
          <p>Collect all weapons in the campaign.</p>
          <li>RE: Master of Unlocking</li>
          <p>Unlock all safes, lockers, strongboxes, and pickable locks.</p>
          <li>survivor</li>
          <p>Complete the game on "Standard" or higher.</p>
          <li>veteran</li>
          <p>Complete the game on "Hardcore" or higher.</p>
          <li>conqueror</li>
          <p>Complete the game on "Nightmare" or higher.</p>
          <li>sensational work!</li>
          <p>Complete the game with an S rank.</p>
          <li>minimalist</li>
          <p>Complete the game without opening the item box.</p>
          <li>i might need these later</li>
          <p>Complete the game using 1 or fewer recovery items.</p>
          <li>sprinter</li>
          <p>Complete the game in under 2 hours of play time.</p>
        </ul>
      </div>
    </div>
  </div>

  <div id="rank" class="d-flex flex-column">
    <h4>rank guide</h4>

    <button data-bs-toggle="collapse" data-bs-target="#assisted"
      >assisted</button
    >
    <div id="assisted" class="collapse">
      <div>
        <h5>S</h5>
        <ul class="list-group">
          <li class="list-group-item">Time: 2 hours 30 min.</li>
          <li class="list-group-item">Saves: 5</li>
        </ul>
      </div>
    </div>

    <button data-bs-toggle="collapse" data-bs-target="#standard"
      >standard</button
    >

    <div id="standard" class="collapse">
      <div>
        <h5>S</h5>
        <ul class="list-group">
          <li class="list-group-item">Time: 2 hours</li>
          <li class="list-group-item">Saves: 5</li>
        </ul>
      </div>
    </div>

    <button data-bs-toggle="collapse" data-bs-target="#hardcore"
      >hardcore</button
    >

    <div id="hardcore" class="collapse">
      <div>
        <h5>S</h5>
        <ul class="list-group">
          <li class="list-group-item">Time: 1 hour 45 min.</li>
          <li class="list-group-item">Saves: 5</li>
        </ul>
      </div>
    </div>
    <button data-bs-toggle="collapse" data-bs-target="#nightmare"
      >nightmare</button
    >

    <div id="nightmare" class="collapse">
      <div>
        <h5>S</h5>
        <ul class="list-group">
          <li class="list-group-item">Time: 2 hours</li>
          <li class="list-group-item">Saves: 5</li>
        </ul>
      </div>
    </div>

    <button data-bs-toggle="collapse" data-bs-target="#inferno">inferno</button>

    <div id="inferno" class="collapse">
      <div>
        <h5>S</h5>
        <ul class="list-group">
          <li class="list-group-item">Time: 2 hours</li>
          <li class="list-group-item">Saves: 5</li>
        </ul>
      </div>
    </div>

    <a href="#top" class="skiplink">Top</a>
  </div>

  <div class="route text-center mb-5" id="route">
    <h4>Train Station Route</h4>
    <p>RE 01 – FA 02 – RA 03 – SA 02 – FO 01</p>
  </div>

  <div class="vaccine text-center" id="vaccine">
    <h4>Lab Vaccine</h4>
    <p>Mid - High - Low</p>
  </div>

  <div class="codes" id="codes">
    <h4>Codes</h4>

    <div class="d-flex justify-content-center">
      <div>
        <h5>Safes</h5>
        <ul>
          <li>
            Downtown Drug Store: left 9, right 3, left 7 |or| left 9, right 1,
            left 8
          </li>
          <li>West Office: left 9, right 15, left 7</li>
          <li>Nurses' Office: right 9, left 3</li>
        </ul>
      </div>

      <div>
        <h5>Lockers</h5>
        <ul>
          <li>2F Shower Room: CAP</li>
          <li>3F Landing: DCM</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="dolls" id="dolls">
    <h4>Charlie Dolls</h4>

    <div class="mx-auto">
      <ol>
        <li>Outside subway after joining Carlos</li>
        <li>In warehouse with a safe inside</li>
        <li>Inside railway company monitor room</li>
        <li>Inside donut shop</li>
        <li>In train substation's control room</li>
        <li>toy store</li>
        <li>behind steel grate in sewers</li>
        <li>near sewer's long stairs</li>
        <li>house beside Kendo gun shop</li>
        <li>Garden in front of rpd</li>
        <li>safety deposit room, rpd</li>
        <li>hallway past dilapidated shelter</li>
        <li>clock tower plaza</li>
        <li>in hospital corrido</li>
        <li>on hospital roof</li>
        <li>garbage can next to nurse room</li>
        <li>entrance to underground hospital passafe</li>
        <li>underground warehouse</li>
        <li>near vaccine machine</li>
        <li>near liquid filled test tube</li>
      </ol>
    </div>
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<style>
  ul li {
    text-transform: capitalize;
  }

  ul p {
    text-transform: capitalize;
    font-size: 12px;
  }

  .list-group-item {
    text-align: center;
  }

  #rank button {
    text-transform: capitalize;
    font-size: 18px;
  }

  #rank h5 {
    font-size: 40px;
    text-align: center;
  }

  @media screen and (max-width: 600px) {
    div {
      padding: 5px;
    }

    #rank {
      padding: 0;
    }
  }
</style>
