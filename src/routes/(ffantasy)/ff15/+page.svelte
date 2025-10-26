<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "Final Fantasy XV";
  import Sections from "$lib/sections.svelte";
  import tombs from "$lib/images/ff15/15tombs.jpg";
  import alstor from "$lib/images/ff15/Alstor-frog.webp";
  import ravatough from "$lib/images/ff15/Ravatough-frog.webp";
  import saxham from "$lib/images/ff15/Saxham-frog.webp";
  import vaullerey from "$lib/images/ff15/Vaulerey-frog.webp";
  import vesperpool from "$lib/images/ff15/Vesperpool-frog.webp";
  import {tengil} from "$lib/jmonsters10.js";
  import {thousandgil} from "$lib/jmonsters.js";

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
      <li><a href="#tombs">tombs</a></li>
    </ul>
  </div>

  <div>
    <h3>Frogs of Legend: Rainbow Frogs</h3>
    <ul class="rainbow">
      <li>
        <p>vesperpool</p>
       <a href={vesperpool} target="_blank">
        <img src={vaullerey} alt="Vesperpool">
       </a>
      </li>
      <li>
        <p>ravatough</p>
        <a href={ravatough} target="_blank">
          <img src={ravatough} alt="Ravatough">
         </a>
      </li>
      <li>
        <p>fort vaullerey</p>
        <a href={vaullerey} target="_blank">
          <img src={vaullerey} alt="Vaullerey">
         </a>
      </li>
      <li>
        <p>saxham</p>
        <a href={saxham} target="_blank">
          <img src={saxham} alt="Saxham">
         </a>
      </li>
      <li>
        <p>alstor slough</p>
        <a href={alstor} target="_blank">
          <img src={alstor} alt="Alstor">
         </a>
      </li>
    </ul>
  </div>

 <div class="jmonsters d-flex">
  <div>
    <h3>Justice Monsters: 10 gil</h3>

  <table class="table">
    <thead>
      <tr>
        <th>chests</th>
        <th>reward</th>
      </tr>
    </thead>
    <tbody>
      {#each tengil as reward }
        <tr>
          <td class="chest">{reward.chests}</td>
          <td>{reward.reward}</td>
        </tr>
      {/each}
    </tbody>
  </table>
  </div>

  <div>
    <h3>Justice Monsters: 10,000 gil</h3>

  <table class="table">
    <thead>
      <tr>
        <th>chests</th>
        <th>reward</th>
      </tr>
    </thead>
    <tbody>
      {#each thousandgil as rewards }
        <tr>
          <td class="chest">{rewards.chests}</td>
          <td>{rewards.reward}</td>
        </tr>
      {/each}
    </tbody>
  </table>
  </div>

 </div>
  <div class="tombs" id="tombs">
    <h3 class="text-center">royal tombs</h3>
   <a href={tombs} target="_blank">
    <img src={tombs} alt="tombs" />
   </a>
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<style>
   .tombs img {
    display: block;
    margin: auto;
    width: 500px;
    height: 300px;
  }

  .rainbow img {
    width: 500px;
    height: 300px;
  }

  .rainbow {
    text-transform: capitalize;
    font-weight: bold;
    font-size: 18px;
  }

  h3 {
    margin-bottom: 30px;
  }

  .chest {
    border-right: 2px solid black;
  }

  .table {
    margin-bottom: 50px;
    width: 75%;
  }

  th {
    text-transform: capitalize;
  }

  td {
    text-transform: capitalize;
  }
</style>
