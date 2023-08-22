<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "resident evil 3 remake";
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

  <div class="route text-center mb-5">
    <h4>Train Station Route</h4>
    <p>RE 01 – FA 02 – RA 03 – SA 02 – FO 01</p>
  </div>

  <div class="vaccine text-center">
    <h4>Lab Vaccine</h4>
    <p>Mid - High - Low</p>
  </div>

  <div class="codes">
    <h4>Codes</h4>

    <h5>Safes</h5>
    <ul>
      <li>
        Downtown Drug Store: left 9, right 3, left 7 |or| left 9, right 1, left
        8
      </li>
      <li>West Office: left 9, right 15, left 7</li>
      <li>Nurses' Office: right 9, left 3</li>
    </ul>

    <h5>Lockers</h5>
    <ul>
      <li>2F Shower Room: CAP</li>
      <li>3F Landing: DCM</li>
    </ul>
  </div>

  <div class="dolls">
    <h4>Charlie Dolls</h4>

    <ol>
      <li>
        <a href="images/charlie1.jpg" target="_blank"
          >Outside subway after joining Carlos</a
        >
      </li>
      <li>
        <a href="images/charlie2.jpg" target="_blank"
          >In warehouse with a safe inside</a
        >
      </li>
      <li>
        <a href="images/charlie3.jpg" target="_blank"
          >Inside railway company monitor room</a
        >
      </li>
      <li>
        <a href="images/charlie4.jpg" target="_blank">Inside donut shop</a>
      </li>
      <li>
        <a href="images/charlie5.jpg" target="_blank"
          >In train substation's control room</a
        >
      </li>
      <li><a href="images/charlie6.jpg" target="_blank">toy store</a></li>
      <li>
        <a href="images/charlie7.jpg" target="_blank"
          >behind steel grate in sewers</a
        >
      </li>
      <li>
        <a href="images/charlie8.jpg" target="_blank"
          >near sewer's long stairs</a
        >
      </li>
      <li>
        <a href="images/charlie9.jpg" target="_blank"
          >house beside Kendo gun shop</a
        >
      </li>
      <li>
        <a href="images/charlie10.jpg" target="_blank">Garden in front of rpd</a
        >
      </li>
      <li>
        <a href="images/charlie11.jpg" target="_blank"
          >safety deposit room, rpd</a
        >
      </li>
      <li>
        <a href="images/charlie12.jpg" target="_blank"
          >hallway past dilapidated shelter</a
        >
      </li>
      <li>
        <a href="images/charlie13.jpg" target="_blank">clock tower plaza</a>
      </li>
      <li>
        <a href="images/charlie14.jpg" target="_blank">in hospital corridor</a>
      </li>
      <li>
        <a href="images/charlie15.jpg" target="_blank">on hospital roof</a>
      </li>
      <li>
        <a href="images/charlie16.jpg" target="_blank"
          >garbage can next to nurse room</a
        >
      </li>
      <li>
        <a href="images/charlie17.jpg" target="_blank"
          >entrance to underground hospital passafe</a
        >
      </li>
      <li>
        <a href="images/charlie18.jpg" target="_blank">underground warehouse</a>
      </li>
      <li>
        <a href="images/charlie19.jpg" target="_blank">near vaccine machine</a>
      </li>
      <li>
        <a href="images/charlie20.jpg" target="_blank"
          >near liquid filled test tube</a
        >
      </li>
    </ol>
  </div>
</div>
