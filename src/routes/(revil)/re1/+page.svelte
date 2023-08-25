<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "resident evil 1 remake";
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

  <div class="weathervane text-center">
    <h4>weathervane puzzle</h4>

    <p>red = west</p>
    <p>blue = north</p>
  </div>

  <div class="v-jolt">
    <h4>Making V-Jolt</h4>

    <div class="w-25 mx-auto">
      <ol>
        <li>Water + chem 3 = chem 4</li>
        <li>chem 4 + chem 6 = chem 10</li>
        <li>Water + chem 6 = chem 7</li>
        <li>chem 7 + chem 10 = chem 17</li>
        <li>chem 17 + chem 3 = V-Jolt</li>
      </ol>
    </div>
  </div>

  <div class="sharks">
    <h4>Aqua Ring</h4>

    <div class="w-25 mx-auto">
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

  <div class="login text-center">
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
