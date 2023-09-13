<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "Assassin's Creed Odyssey";
  import Sections from "$lib/sections.svelte";

  import * as components from "$lib/odysseyarr.js";

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
      <li><a href="#pilgrim">pilgrim set</a></li>
      <li><a href="#tombs">tombs</a></li>
    </ul>
  </div>

  <div class="pilgrim" id="pilgrim">
    <h4>pilgrim set</h4>
    <p class="text-center">All pieces = -100% Shadow of Nyx cost</p>

    <ol>
      <li>Hood</li>
      <p>
        Eleusis Telesterion, Sanctuary of Eleusis, west of Attika on the Sacred
        Plain of Demeter
      </p>
      <li>Garment</li>
      <p>Temple of Athena in Sparta</p>
      <li>Gloves</li>
      <p>Akropolis temple in Argos</p>
      <li>Belt</li>
      <p>Pandora's Cove area in Malis, Temple of the Golden-Bowed Goddess</p>
      <li>Boots</li>
      <p>Temple of Britomartis, Little Egypt</p>
    </ol>
  </div>

  <div class="tombs" id="tombs">
    <h4>tomb locations</h4>

    <h3>megaris</h3>
    <h5>tomb of alkathous</h5>
    <img src={components.tomb1} alt="tomb" />

    <h3>phokis</h3>
    <h5>tomb of the first pythia</h5>
    <img src={components.tomb2} alt="tomb" />

    <h3>attika</h3>
    <h5>tomb of eteokles</h5>
    <img src={components.tomb3} alt="tomb" />
    <h5>tomb of ajax</h5>
    <img src={components.tomb4} alt="tomb" />

    <h3>euboea</h3>
    <h5>atemision tomb</h5>
    <img src={components.tomb5} alt="tomb" />

    <h3>argolis</h3>
    <h5>agamemnon's tomb</h5>
    <img src={components.tomb6} alt="tomb" />
    <h5>pheidon's tomb</h5>
    <img src={components.tomb7} alt="tomb" />

    <h3>naxos</h3>
    <h5>giant heroes burial ground</h5>
    <img src={components.tomb8} alt="tomb" />

    <h3>paros</h3>
    <h5>alkaios tomb</h5>
    <img src={components.tomb9} alt="tomb" />

    <h3>delos</h3>
    <h5>tomb of brizo</h5>
    <img src={components.tomb10} alt="tomb" />

    <h3>kos</h3>
    <h5>tomb of plybotes</h5>
    <img src={components.tomb11} alt="tomb" />

    <h3>lakonia</h3>
    <h5>tomb of the forgotten hero</h5>
    <img src={components.tomb12} alt="tomb" />

    <h3>arkadia</h3>
    <h5>waterfall of styx</h5>
    <img src={components.tomb13} alt="tomb" />
    <h5>tomb of the daughter of atlas</h5>
    <img src={components.tomb14} alt="tomb" />

    <h3>elis</h3>
    <h5>tomb of the first champion</h5>
    <img src={components.tomb15} alt="tomb" />
    <h5>destroyed house of oinomaos</h5>
    <img src={components.tomb16} alt="tomb" />

    <h3>boeotia</h3>
    <h5>tomb of orion</h5>
    <img src={components.tomb17} alt="tomb" />

    <h3>achaia</h3>
    <h5>tomb of euryples</h5>
    <img src={components.tomb18} alt="tomb" />

    <h3>thasos</h3>
    <h5>parmenon tomb</h5>
    <img src={components.tomb19} alt="tomb" />

    <h3>lemnos</h3>
    <h5>abandoned tomb</h5>
    <img src={components.tomb20} alt="tomb" />

    <h3>chios</h3>
    <h5>stony sepulchre</h5>
    <img src={components.tomb21} alt="tomb" />

    <h3>lesbos</h3>
    <h5>tomb of orpheus</h5>
    <img src={components.tomb22} alt="tomb" />
  </div>

  <a href="#top" class="skiplink">Top</a>
</div>

<style>
  .pilgrim li {
    font-weight: bold;
  }
</style>
