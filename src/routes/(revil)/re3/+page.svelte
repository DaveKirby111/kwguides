<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "Resident Evil 3 Remake";
  import Sections from "$lib/sections.svelte";

  const sections = [
    {
      name: "guides",
      link: "#guides",
    },
  ];
</script>

<Sections {sections} />

<div id="guides" class="guides">
  <h2>guides</h2>

  <div class="guide-sections">
    <p class="fw-bold text-decoration-underline">Sections</p>
    <ul class="skip">
      <li><a href="#route">train station route</a></li>
      <li><a href="#vaccine">lab vaccine</a></li>
      <li><a href="#codes">codes</a></li>
      <li><a href="#dolls">charlie dolls</a></li>
    </ul>
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
  @media screen and (max-width: 600px) {
    div {
      padding: 5px;
    }
  }
</style>
