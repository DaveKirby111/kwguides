<script>
    
    import { pageTitle } from "$lib/stores.js";
    pageTitle.set("Fallout: New Vegas");
    import Sections from "$lib/sections.svelte";

    const sections = [
      {
      name: "console",
      link: "#console",
    },
    
    {
      name: "guides",
      link: "#guides",
    },
  ];

  const commands = [
    {
      name: "god mode",
      input: "tgm",
      desc: "toggle god mode. Infinite health, Inf. ammo, etc.",
    },

    {
      name: "toggle collision",
      input: "tcl",
      desc: "move through the world.",
    },

    {
      name: "money",
      input: "player.additem f (amount)",
      desc: "give the player caps",
    },
    
  ];
  

  </script>
  
  <Sections {sections} />

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

  <div id="guides" class="guides">

    <h2>guides</h2>

    <div class="guide-sections">
        <p class="fw-bold text-decoration-underline">Sections</p>
        <ul class="skip">
          <li><a href="#tombs">tombs</a></li>
        </ul>
      </div>

      <a href="#top" class="skiplink">Top</a>
  </div>
  
  
  
  <style>
    
  </style>
  