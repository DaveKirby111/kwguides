<script>
    
    import { pageTitle } from "$lib/stores.js";
    pageTitle.set("Tomb Raider");
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
  