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

    <h2>guides</h2>

    <div class="guide-sections">
        <p class="fw-bold text-decoration-underline">Sections</p>
        <ul class="skip">
          <li><a href="#trophies">trophies</a></li>
        </ul>
      </div>

      <div id="trophies">
        <h4>trophies</h4>
        <div>
          <h5>100% completion</h5>
          <ul>
        <div class="d-flex">
          <div>
            <li>true survivor</li>
            <p>Unlock every Tomb Raider trophy.</p>
            <li>bookworm</li>
            <p>Find 25% of all documents.</p>
            <li>historian</li>
            <p>Find 75% of all documents.</p>
            <li>relic hunter</li>
            <p>Collect 25% of all relics.</p>
            <li>archeologist</li>
            <p>Collect 75% of all relics.</p>
            <li>looking for trouble</li>
            <p>Find 25% of GPS caches.</p>
            <li>Bag Full O' Cache</li>
            <p>Find 75% of GPS caches.</p>
            <li>no stone left unturned</li>
            <p>Find all documents, relics and GPS caches.</p>
            <li>scrounger</li>
            <p>Collect 5000 pieces of salvage.</p>
            <li>picky</li>
            <p>Loot 200 enemies.</p>
            <li>clever girl</li>
            <p>Purchase all skills in one category.</p>
            <li>lethal</li>
            <p>Purchase all skills in all categories.</p>
            <li>now we're getting serious</li>
            <p>Fully mod and completely upgrade any weapon.</p>
            <li>the professional</li>
            <p>Fully mod and completely upgrade all weapons.</p>
            <li>big game hunter</li>
            <p>Kill and loot 10 large animals (deer, boar, wolves).</p>
            <li>tastes like chicken!</li>
            <p>Kill and loot 10 small animals (rabbits, chickens, rats).</p>
            <li>feather duster</li>
            <p>Kill and loot 10 flying animals (crows and gulls).</p>
            <li>sharp shooter</li>
            <p>Perform 50 headshot kills in the single player campaign.</p>
            <li>predator</li>
            <p>Kill 50 enemies with the bow.</p>
            <li>equalizer</li>
            <p>Kill 75 enemies with the rifle.</p>
            <li>widowmaker</li>
            <p>Kill 40 enemies with the shotgun.</p>
            <li>gunslinger</li>
            <p>Kill 35 enemies with the pistol.</p>
            <li>epic fumble</li>
            <p>Force an enemy to drop dynamite that kills two people when exploding.</p>
            <li>get over here!</li>
            <p>Rope pull 5 enemies off edges.</p>
            <li>opportunist</li>
            <p>Kill 25 unaware enemies.</p>
            <li>down and dirty</li>
            <p>Perform 15 finishers.</p>
          </div>
          <div>
            <li>deadeye</li>
            <p>Shoot 10 enemies off zip lines.</p>
            <li>former adventurer</li>
            <p>Incapacitate 25 enemies with dodge counter.</p>
            <li>one smart cookie</li>
            <p>Complete one optional tomb.</p>
            <li>intellectualy superior</li>
            <p>Complete all optional tombs.</p>
            <li>unfinished business</li>
            <p>Complete one challenge.</p>
            <li>inconceivable!</li>
            <p>Complete all challenges.</p>
            <li>a survivor is born</li>
            <p>Complete the game.</p>
            <li>boom goes the dynamite</li>
            <p>Shoot a bundle of dynamite out of the air.</p>
            <li>crab cakes</li>
            <p>Kill FeeFee the crab.</p>
            <li>chatterbox</li>
            <p>Complete all conversations with the Endurance crew.</p>
            <li>adventurer</li>
            <p>Complete a match in all multiplayer modes.</p>
            <li>artilleryman</li>
            <p>Kill 20 enemy players in multiplayer using a turret.</p>
            <li>down boy!</li>
            <p>Kill a zip-lining enemy player in multiplayer.</p>
            <li>entrapment</li>
            <p>Catch a player in a snare trap in multiplayer.</p>
            <li>escapist</li>
            <p>Survive 10 explosions in multiplayer.</p>
            <li>good samaritan</li>
            <p>Revive a teammate in a multiplayer match.</p>
            <li>i'm all that!</li>
            <p>Win a ranked match in every multiplayer mode.</p>
            <li>sole survivor</li>
            <p>In multiplayer, be the only player on your team that isn't dead or downed.</p>
            <li>lights out</li>
            <p>Kill 10 multiplayer enemies using your melee attack.</p>
            <li>master blaster</li>
            <p>Kill 2 multiplayer enemies with a single explosive.</p>
            <li>monkey around</li>
            <p>In multiplayer, escape death 3 times by using the rope ascender.</p>
            <li>narcissistic</li>
            <p>Purchase a new multiplayer character.</p>
            <li>on my way up</li>
            <p>Reach level 10 in multiplayer.</p>
            <li>shopaholic</li>
            <p>Buy every upgrade and character in multiplayer.</p>
            <li>true commitment</li>
            <p>Reach level 60 in multiplayer.</p>
          </div>
        </div>
           
          </ul>
        </div>
      </div>

      <a href="#top" class="skiplink">Top</a>
  </div>
  
  
  
  <style>

    ul li {
      text-transform: capitalize;
    }

    ul p {
      text-transform: capitalize;
      font-size: 12px;
    }
    
  </style>
  