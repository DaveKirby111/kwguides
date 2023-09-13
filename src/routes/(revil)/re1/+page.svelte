<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "Resident Evil 1 Remake";
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
      <li><a href="#wvane">weathervane</a></li>
      <li><a href="#vjolt">V-Jolt</a></li>
      <li><a href="#sharks">aqua ring</a></li>
      <li><a href="#lab">lab</a></li>
    </ul>
  </div>

  <div class="weathervane text-center" id="wvane">
    <h4>weathervane puzzle</h4>

    <p>red = west</p>
    <p>blue = north</p>
  </div>

  <div class="v-jolt" id="vjolt">
    <h4>Making V-Jolt</h4>

    <div class="mx-auto">
      <ol>
        <li>Water + chem 3 = chem 4</li>
        <li>chem 4 + chem 6 = chem 10</li>
        <li>Water + chem 6 = chem 7</li>
        <li>chem 7 + chem 10 = chem 17</li>
        <li>chem 17 + chem 3 = V-Jolt</li>
      </ol>
    </div>
  </div>

  <div class="sharks" id="sharks">
    <h4>Aqua Ring</h4>

    <div class="mx-auto">
      <ol>
        <li>Check center console</li>
        <li>Check right console</li>
        <li>Check left console</li>
        <li>Check pressure console</li>
        <li>Check right console</li>
        <li>Check left console</li>
        <li>Check center console</li>
      </ol>
    </div>
  </div>

  <div class="login text-center" id="lab">
    <h4>Lab Username and Password</h4>

    <p>Username: JOHN</p>
    <p>Password: ADA</p>
    <p>B2F - pass: CELL</p>
    <p>B3F</p>
  </div>

  <div class="panel text-center">
    <h4>Lab Number Panel</h4>
    <p>Code: 8462</p>
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
