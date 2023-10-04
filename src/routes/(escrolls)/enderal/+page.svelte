<script>
  import { pageTitle } from "$lib/stores.js";
  pageTitle.set("Enderal");
  import Sections from "$lib/sections.svelte";

  const sections = [
    {
      name: "guides",
      link: "#guides",
    },
  ];

  const commands = [
    {
      name: "god mode",
      input: "tgm",
      desc: "toggle god mode. Infinite health, magicka, fatigue",
    },

    {
      name: "money",
      input: "player.additem f (amount)",
      desc: "give the player gold",
    },

    {
      name: "lockpicks",
      input: "player.additem a (amount)",
      desc: "give the player lockpicks",
    },

    {
      name: "memory points",
      input: "set talentpoints to {Number of points wanted}",
      desc: "give memory points",
    },

    {
      name: "map markers",
      input: "tmm (1 or 0)",
      desc: "toggle map markers",
    },
  ];
</script>

<Sections {sections} />

<div id="guides" class="guides">
  <div class="guide-sections">
    <p class="fw-bold text-decoration-underline">Sections</p>
    <ul class="skip">
      <li><a href="#console">console</a></li>
    </ul>
  </div>

  <div class="intro">
    <h4>intro</h4>

    <h5>what is enderal</h5>

    <p>
      Enderal is a total conversion mod for the Elder Scrolls V: Skyrim. It
      contains it's own world and lore but it runs on Skyrim's engine and uses
      mechanics, items, and features from Skyrim. It is even dependant on the
      user owning a copy of Skyrim in order to play it. It is however, listed on
      Steam as being it's own game. Because it is so dependant on Skyrim I am
      treating it as a mod rather than it's own game, and putting it under the
      Elder Scrolls title.
    </p>
  </div>

  <div id="console" class="console">
    <h2>console commands</h2>

    <table
      class="table table-borderless table-dark table-striped table-responsive"
    >
      <thead class="text-capitalize">
        <tr>
          <th>name</th>
          <th>command</th>
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

  <a href="#top" class="skiplink">Top</a>
</div>

<style>
</style>
