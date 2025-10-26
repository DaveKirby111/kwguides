<script>
  import { pageTitle } from "$lib/stores.js";
  pageTitle.set("Witcher 2: Assassins of Kings");
  import Sections from "$lib/sections.svelte";
  import Bloodsword from "$lib/images/witcher2/bloodsword.webp";
  import Gargoyls from "$lib/images/witcher2/gargoyls.webp";

  // const sections = [
  //   {
  //     name: "guides",
  //     link: "#guides",
  //   },
  // ];
</script>

<!-- <Sections {sections} /> -->

<div id="guides" class="guides">
  <div class="guide-sections">
    <p class="fw-bold text-decoration-underline">Sections</p>
    <ul class="skip">
      <li><a href="#tombs">Side Quests</a></li>
    </ul>
  </div>

  <div>
  <h3>Experience bonus: destroy 10 training dummies.</h3>
  <p>Prologue: 5 in the camp</p>
  <p>Chapter 1: 2 in the nonhuman exit, 2 in the guardhouse, 2 in Loredo's place</p>
  </div>

  <div>
    <h3>Blood Curse</h3>
    <p>the ritual: order to create the circle</p>
    <ol>
      <li>petrified bread</li>
      <li>black candles</li>
      <li>goat skull</li>
      <li>scorched tree</li>
      <li>raven's corpse</li>
      <li>sour milk</li>
      <li>pixie ring</li>
    </ol>
  </div>

  <div>
    <h3>Free swords to pick up:</h3>
    <p><b>Chapter 1:</b></p>
    <p>Silver= Sword of Kaer Morhen, after meeting Iorveth in Arachas' Lair</p>
    <p><b>chapter 2:</b></p>
    <p>Steel= Roche path- skeleton submerged in water near Sabrina's shrine</p>
    <p>Silver= Roche path- in the tunnels of Vergen before meeting Zoltan and Saskia.</p>
    <a href={Bloodsword} target="_blank"><img src={Bloodsword} alt="bloodsword" /></a>
    <p><b>Chapter 3:</b></p>
    <p>Silver= both paths- Deithwen - outside the entrance of Loc Muine, guarded by 2 Arachas</p>
  </div>

  <div id="side">
    <h3>side quests</h3>

    <div>
      <p class="fw-bold text-decoration-underline">Collapse tunnels</p>
      <p>when it says collapse tunnels using beehives, it means Grapeshot.</p>
    </div>
  <div id="sideq">
    <p class="fw-bold text-decoration-underline">Little Sisters</p>
    <p>Order:</p>
    <ul class="sisters">
      <li>v</li>
      <li>diamond</li>
      <li>upside down v</li>
    </ul>
  </div>

  <div id="sideq">
    <p class="fw-bold text-decoration-underline">With Flickering Heart</p>
    <p>Iorveth path only</p>
    <p>buy surgical tools before examing bodies in the catacombs.</p>
    <p>Dandelion:</p>
    <ul>
      <li>If our bodies...</li>
      <li>My heart...</li>
      <li>Or treat it...</li>
    </ul>
  </div>

  <div id="sideq">
    <p class="fw-bold text-decoration-underline">From a Bygone Era.</p>
    <p>password: Zi, Uddu-ya, la la, Gat, Exa, Nibbit, Kanpa, Gat, Uddu-zi</p>
  </div>

  <div id="sideq">
    <p class="fw-bold text-decoration-underline">Harpy Contract</p>
    <p>Iorveth path only</p>
    <ul>
      <li>first buy Harpy traps</li>
      <li>4 nests in the old quarry</li>
      <li>continue Hunting Magic quest to get into the Harpy lair.</li>
    </ul>
  </div>

  <div id="sideq">
    <p class="fw-bold text-decoration-underline">Lillies and Vipers</p>
    <p>Roche path only</p>
    <p>testing the letter:</p>
    <ol>
      <li>add lime</li>
      <li>add water</li>
      <li>add guano</li>
      <li>add heat to flask and capture vapors</li>
    </ol>
  </div>

  <div id="sideq">
    <p class="fw-bold text-decoration-underline">Gargoyle Contract</p>
    <a href={Gargoyls} target="_blank"><img src={Gargoyls} alt="gargoyls" /></a>
   <p>runes:</p>
   <ul>
    <li>animal- S shaped rune</li>
    <li>time- hourglass shaped rune</li>
    <li>art- harp shaped rune</li>
    <li>sky- diamond shaped rune</li>
   </ul>
   <p>how to solve rune rooms:</p>
   <p><i>A doe's long shadow</i></p>
   <p><i>The moon quietly moans</i></p>
   <p><i>It is autumn already</i></p>
   <p>answer= animal, sky, art, time</p>
  </div>
  </div>

  <a href="#top" class="skiplink">Top</a>
</div>

<style>
  h3{
    text-transform: capitalize;
  }

  p{
    text-transform: capitalize;
  }

  li{
    text-transform: capitalize;
  }

  img{
    width: 400px;
    height: 200px;
  }

  #sideq{
    margin-bottom: 30px;
  }

.sisters {
text-transform: capitalize;
}
</style>
