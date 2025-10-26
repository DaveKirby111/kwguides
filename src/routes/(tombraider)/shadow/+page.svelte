<script>
    
    import { pageTitle } from "$lib/stores.js";
    pageTitle.set("Shadow of the Tomb Raider");
    import Sections from "$lib/sections.svelte";

  //   const sections = [
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
          <li><a href="#trophies">trophies</a></li>
        </ul>
      </div>

      <div id="trophies">
        <h4>trophies</h4>

        <div class="d-flex">
          <div>
            <h5>story</h5>
            <ul>
              <li>chain gang</li>
              <p>Perform the Serpent's Fury 3 times</p>
              <li>like a shadow</li>
              <p>Perform a Stealth Takedown on 25 enemies</p>
              <li>surprise!</li>
              <p>Perform 5 Eagle's Talon takedowns</p>
              <li>tables turned</li>
              <p>Kill 5 enemies while they are searching for Lara</p>
              <li>look, over there!</li>
              <p>Kill 3 enemies while they are distracted</p>
              <li>total party kill</li>
              <p>Kill 5 enemies with friendly fire</p>
              <li>playing with fire</li>
              <p>Burn 2 enemies simultaneously</p>
              <li>gunslinger</li>
              <p>Perform 3 headshots in 3 seconds with the pistol</p>
              <li>last known position</li>
              <p>Lose the enemy 10 times</p>
              <li>sixth sense</li>
              <p>Hunt and kill 10 enemies while Perception is active</p>
              <li>in the moment</li>
              <p>Kill 10 enemies while Focus is active</p>
              <li>made to endure</li>
              <p>Takedown 10 enemies while Endurance is active</p>
              <li>marksman</li>
              <p>Perform 20 headshots with the bow</p>
              <li>first blood</li>
              <p>Perform a Stealth Takedown from a mud-covered wall</p>
              <li>path of the stars</li>
              <p>Decipher the Path of the Stars</p>
              <li>Día de Muertos</li>
              <p>Remove the dagger from the Temple of the Moon</p>
              <li>recipe for disaster</li>
              <p>Survive the flood</p>
              <li>survival instincts</li>
              <p>Defeat the Empress Jaguar</p>
              <li>fire of life</li>
              <p>Enter the Temple of Life's inner chamber</p>
              <li>the hidden city</li>
              <p>Find Paititi</p>
              <li>the underworld</li>
              <p>Get out of the Cenote alive</p>
              <li>family ties</li>
              <p>Free Unuratu from prison</p>
              <li>heart of the serpent</li>
              <p>Find the Mission of San Juan</p>
              <li>the chosen one</li>
              <p>Find the Silver Box of Ix Chel</p>
              <li>Back to Where We Started</li>
              <p>Return to Paititi</p>
              <li>Queen of the Damned</li>
              <p>Make an unlikely ally</p>
              <li>Quite the Adventure</li>
              <p>Finish the main storyline</p>
              <li>Smart and Resourceful</li>
              <p>Complete Shadow of the Tomb Raider on Smart and Resourceful difficulty</p>
            </ul>
          </div>
          <div>
            <h5>100% completion</h5>
            <ul>
              <li>treasures from the past</li>
              <p>Decipher a Monolith</p>
              <li>archeologist</li>
              <p>Complete an Artifact Collection</p>
              <li>dr. croft</li>
              <p>Complete all Artifact Collections</p>
              <li>stele hunter</li>
              <p>Complete 3 main game Challenge Tombs</p>
              <li>tomb raider</li>
              <p>Complete all main game Challenge Tombs</p>
              <li>to the nines</li>
              <p>restore and equip a matching vestige outfit</p>
              <li>makeshift arsenal</li>
              <p>Fully upgrade a weapon</p>
              <li>up to the challenge</li>
              <p>Complete 5 Challenges</p>
              <li>resting places</li>
              <p>Uncover 3 main game Crypts' secrets</p>
              <li>thread the past</li>
              <p>Restore 5 vestige outfit pieces</p>
              <li>help thy neighbor</li>
              <p>Complete a Side Mission</p>
              <li>good samaritan</li>
              <p>Complete 8 Side Missions</p>
              <li>first steps</li>
              <p>Purchase a Skill</p>
              <li>specialized</li>
              <p>Earn all Skills in one category</p>
              <li>treasure hunter</li>
              <p>Find and open all the main game Conquistador treasure chests</p>
              <li>asking price</li>
              <p>Buy an item from a merchant</p>
              <li>beast of legend</li>
              <p>Defeat the Nahual</p>
              <li>Como Te Llama</li>
              <p>Pet 5 llamas</p>
              <li>underwater archeologist</li>
              <p>Collect 5 underwater Artifacts</p>
              <li>new heights</li>
              <p>Complete a climb after finding the Overhang Climbing Gear</p>
              <li>that's a knife!</li>
              <p>Fully upgrade the knife</p>
              <li>zoologist</li>
              <p>Collect 20 critters</p>
              <li>legendary hunter</li>
              <p>Hunt and loot 5 rare animals</p>
              <li>untold riches</li>
              <p>Gather 40 gold ore</p>
              <li>unwelcome guests</li>
              <p>Get rid of the pillagers outside of Kuwaq Yaku</p>
              <li>i believe hakan fly</li>
              <p>Rescue Hakan from the cultists</p>
              <li>hearts and minds</li>
              <p>Retrieve Manko's Necklace</p>
              <li>on the go</li>
              <p>Craft special ammunition 50 times</p>
              <li>point of interest</li>
              <p>Learn of 5 interesting locations from civilians</p>
              <li>thanksgiving</li>
              <p>Shoot a turkey with a Flare Round</p>
              <li>better equipped</li>
              <p>Get 3 pieces of equipment</p>
              <li>completionist</li>
              <p>Reach 100% completion</p>
            </ul>
          </div>
          <div>
            <h5>deadly obsession playthrough</h5>
            <ul>
              <li>chalice of toment</li>
              <p>Earn all Trophies</p>
              <li>rite of passage</li>
              <p>Complete Shadow of the Tomb Raider on Rite of Passage difficulty</p>
              <li>one with the jungle</li>
              <p>Complete Shadow of the Tomb Raider on One with the Jungle difficulty</p>
              <li>deadly obsession</li>
              <p>Complete Shadow of the Tomb Raider on Deadly Obsession difficulty</p>
            </ul>
          </div>
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
  