<script>
    
    import { pageTitle } from "$lib/stores.js";
    pageTitle.set("Rise of the Tomb Raider");
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
          <li><a href="#bties">blood ties</a></li>
        </ul>
      </div>

      <div id="trophies">
        <h4>trophies</h4>

       <div class="d-flex">
        <div>
          <h5>story</h5>
          <ul>
            <li>the price of truth</li>
            <p>finish the game on any difficulty</p>
            <li>quite a tumble</li>
            <p>survive the avalanche</p>
            <li>Following in Father's Footsteps</li>
            <p>enter the syrian tomb</p>
            <li>Tougher Than She Looks</li>
            <p>Survive a night in the Siberian wilderness</p>
            <li>Strange Acquaintance</li>
            <p>Rescue Jacob from the gulag</p>
            <li>Taking the High Road</li>
            <p>Light the signal fire in the Remnant Valley</p>
            <li>A Helping Hand</li>
            <p>Defend Remnant home from the Looter Invasion</p>
            <li>The Key To It All</li>
            <p>Recover the Atlas</p>
            <li>Whatever It Takes</li>
            <p>Rescue Jonah from Konstantin</p>
            <li>The Road Less Travelled</li>
            <p>Unlock the path to Kitezh</p>
            <li>Ultimate Survivor</li>
            <p>Finish the game on Survivor difficulty</p>
          </ul>
        </div>
        <div>
          <h5>100% open world</h5>
          <ul>
            <li>reading the past</li>
            <p>translate a monolith</p>
            <li>fluent</li>
            <p>Reach max proficiency in any language</p>
            <li>keen eye</li>
            <p>Unearth 40 Survival Caches</p>
            <li>looking for trouble</li>
            <p>Complete 5 Challenges</p>
            <li>good samaritan</li>
            <p>Complete 3 Missions</p>
            <li>challenging</li>
            <p>Complete any Challenge Tomb</p>
            <li>tomb raider</li>
            <p>Complete all Challenge Tombs</p>
            <li>Woman of the People</li>
            <p>complete every mission</p>
            <li>truth seeker</li>
            <p>Collect 25% of all narrative assets (relics, murals and documents)</p>
            <li>voices of the past</li>
            <p>Collect 75% of all narrative assets (relics, murals and documents)</p>
            <li>compulsive</li>
            <p>complete every challenge</p>
            <li>the chosen few</li>
            <p>Uncover the remains of all Jacob's disciples</p>
            <li>no guts, no glory</li>
            <p>Perform a 2.5 second or longer swan dive</p>
            <li>no stone unturned</li>
            <p>Achieve 100% game completion</p>
          </ul>
        </div>
       </div>
       <div class="d-flex">
        <div>
          <h5>open world cleanup</h5>
          <ul>
            <li>firestarter</li>
            <p>Defeat 2 enemies or more using a single Molotov Cocktail</p>
            <li>bar brawl</li>
            <p>Melee kill an enemy using a bottle</p>
            <li>rapid recovery</li>
            <p>Heal yourself in combat 3 times</p>
            <li>renegade</li>
            <p>Melee 5 enemies off a ledge</p>
            <li>fearless</li>
            <p>Defeat a Deathless Swordsman using only melee attacks and a finisher</p> 
            <li>fall guys</li>
            <p>Kill 10 enemies by shooting them in the leg</p>
            <li>one-sided conversation</li>
            <p>Stealth kill an enemy while they are having a conversation</p>
            <li>glub glub glub</li>
            <p>Drown 3 enemies using a water finisher</p>
            <li>blade of justice</li>
            <p>Perform 25 special stealth kills with the knife</p>
            <li>was that really necessary?</li>
            <p>Kill any animal with an explosive</p>
            <li>weaponsmith</li>
            <p>Fully upgrade any weapon</p>
            <li>craftswoman</li>
            <p>Craft 5 pieces of Equipment</p>
            <li>master fletcher</li>
            <p>Craft 25 of each special arrow type (Fire, Grenade, Poison)</p>
            <li>self-improvement junkie</li>
            <p>Purchase all skills in a single category</p>
            <li>laying down the law</li>
            <p>Kill 6 enemies with the Revolver without reloading</p>
            <li>english pedigree</li>
            <p>Headshot an enemy with an arrow from a distance beyond 25m</p>
            <li>chemical waarfare</li>
            <p>Kill 5 enemies with one Poison Arrow</p>
            <li>dead ringer</li>
            <p>Get 25 headshots using the Bolt-Action Rifle</p>
            <li>quick and painless</li>
            <p>Shoot 15 deer in the heart</p>
            <li>trick shot</li>
            <p>Shoot a bottle out of the air</p>
            <li>rotisserie</li>
            <p>Shoot a chicken out of the air with a fire arrow</p>
            <li>avid shopper</li>
            <p>Purchase all items from the supply shack</p>
            <li>quiet time</li>
            <p>Find the best seat in the house</p>
            <li>bacon!</li>
            <p>Kill a razorback boar using a Molotov cocktail</p>
            <li>huntress</li>
            <p>Kill 50 animals while wearing the Huntress outfit</p>
            <li>siberian ranger</li>
            <p>Beat 15 combat encounters after completing the game</p>
          </ul>
        </div>
        <div>
          <h5>expedition mode</h5>
          <ul>
            <li>triple threat</li>
            <p>Kill 3 enemies with 1 Shotgun blast</p>
            <li>a trusty old friend</li>
            <p>Kill 5 enemies within 10 seconds using any rifle</p>
            <li>paying respects</li>
            <p>Attend a funeral</p>
            <li>zipper</li>
            <p>Perform a manual zip line transfer</p>
          </ul>
        </div>
        <div>
          <h5>score attack!</h5>
          <ul>
            <li>platinum</li>
            <p>You unlocked every trophy in the game</p>
            <li>Quite the Collector</li>
            <p>collect 150 cards</p>
            <li>These Belong in A Museum</li>
            <p>collect 300 cards</p>
            <li>way to go</li>
            <p>Complete every level in Score Attack with a bronze score or better</p>
            <li>golden child</li>
            <p>Complete every level in Score Attack with a gold score</p>
            <li>gilded</li>
            <p>Complete a level in Score Attack with a gold score</p>
            <li>well begun is half done</li>
            <p>Complete 10 levels in Score Attack with a gold score</p>
            <li>My Own Worst Enemy</li>
            <p>Complete a level in Score Attack with a score multiplier of 2 or more</p>
            <li>iron will</li>
            <p>Complete a level in Score Attack using 5 cards</p>
            <li>That All You Got?</li>
            <p>Complete 3 Replay Challenges in one Score Attack</p>
            <li>untouchable</li>
            <p>Replay 5 different levels without taking any damage</p>
          </ul>
        </div>
       </div>
      </div>

      <div id="bties">
        <h4>blood ties</h4>

        <h5>safe code</h5>
        <ol>
          <li>Lara's expedition treasure: Egyptian Crown in library trunk. The crown made of paper depicts an image of two birds. Examine the Hieroglyphics Worksheet to match the birds with the number 5.</li>

          <li>Lara's Dad's favorite painting by Amelia: the painting with red cubes. Examine the painting she describes in the studio. There are 4.</li>

          <li>Wedding Anniversary: Amelia's necklace given to her on the 13th of October, in the Bedroom. A note from Amelia describing their wedding four days before her birthday, means that the wedding was on October 9.</li>
        </ol>

        <p class="fw-bold">Safe Combo: 5-4-9</p>

        <h5>relics</h5>
        <ol>
          
            <p>richard croft study</p>
            <li>A photo of little Lara on Richard Croft's desk.</li>
            <li>Richard's framed diploma sitting on the small table near the window behind the desk.</li>
            <li>A photo of Lara, Richard, and Ana sitting on a shelf on the right side of the room when facing the exit.</li>
            <li>A carved marble bust sitting on a small table near the previous photo.</li>
            <li>An African mask stored in a cabinet to the left of the carved bust. </li>
            <li>A map of Syria spread out on the drafting table on the left side of the room.</li>
            <li>A copy of Richard's book stored in a cabinet to the right of the drafting table.</li>

            <p>corridor to study</p>
            <li>A hand-drawn map Lara made as a child, sitting on the boxes on the right side of the corridor. </li>
            <li>An Ankh from Richard's collection, is in a glass case opposite the servants' entrance.</li>

            <p>main hall upper level</p>
            <li> Open the lacquered cabinet.</li>
            <li>A cigarette case sitting on a windowsill. </li>

            <p>main hall lower level</p>
            <li> In the main entryway, on the far side of the room, is a box containing a FLASHLIGHT. This also counts as relic #12.</li>
            <li>An Ouroboros amulet in a glass case. </li>
            <li>Near the rubble-strewn hole in the floor to find another ancestor's bust sitting in an alcove. </li>

            <p>wine cellar</p>
            <li>After a brief flashback, examine the chessboard Lara and Winston used to use. </li>
            <li>Continue through the doorway that was previously blocked by the cart. Just beyond the doorway is relic #16, a crystal decanter.</li>

            <p>basement tunnels</p>
            <li>Turn left at the painted wooden bird figure. Proceed straight ahead, keeping the long basement wall on your right, until you come to the far corner. Turn left here, then right, then left again, still walking through the rusty water. As you step out of the water onto the earthen floor, go around the wooden barrier to the back right corner to find Lara's mummified teddy bear in its tiny sarcophagus. </li>

            <li>Watch out for the "deadly trap" laid out ahead. A yellow plastic box suspended from the ceiling with a rope snare below. In the middle of the snare is a Trap Mechanism crafted by Winston.</li>

            <li>Squeeze through the gap between the piled-up wooden crates. Then immediately make a U-turn to the left to find the Anubis bust you glimpsed through the fence earlier. </li>

            <li>Before entering the LIBRARY a set of renovation plans,</li>

            <p>library</p>
            <li>In a metal box underneath document #19 you'll find the LIGHTER, an important piece of gear. </li>
            <li>A drawing of a tiger Lara did when she was little, on the window seat next to a toy dinosaur and helicopter.</li>
            <li> Young Lara's hieroglyphics worksheet, Sitting on a table on the east side of the room.</li>
            <li>Underneath the worksheet you'll find an elaborately bound book about hieroglyphs from Richard's collection.</li>
            <li>On the table opposite the last two items is a note from Winston to Lara.</li>
            <li>An old photograph taken in the library. Small upper level section.</li>
            <li>Lara's childhood Expedition Maps, sitting on top of a locked chest.</li>
            <li>Climb or jump down to the floor. Stand near the fireplace and hold Interact to use the LIGHTER to light the fire. Then press Interact again to hold the map you just found up to the fire. This activates the invisible ink so you can see the complete map. The revealed map counts as a separate relic #28.</li>
            <li>Master Key</li>
            <li>Use the rolling library ladder to climb back to the upper level. Go around to the right and use the key to open the chest upon which the expedition map was resting. Inside is relic #30, Lara's homemade Egyptian crown.</li>

            <p>main hall upper level - part 2</p>
            <li>Now that you have the key you can unlock the chest here to find relic #31, the Croft Family Crest. </li>

            <p>master bedroom</p>
            <li>Amelia's wedding ring, sitting on the bed.</li>
            <li>Amelia's perfume bottle, on the dressing table. </li>
            <li>A photo of Amelia on her wedding day, on a cloth-draped box to the left of the dressing table. </li>
            <li>On the bedside table is a small box containing a necklace given to Lara's mother by her father as a birthday gift. </li>
            <li>A carved bust of Richard Croft sits on a table opposite the fireplace. </li>
            <li>Richard's pocket watch is on the carved wooden chest nearby.</li>

            <p>amelia's atelier</p>
            <li>One of two framed photos near the large painting of the curved glass buildings.</li>
            <li>The other photo in that same area.</li>
            <li>Climb the ladder to the upper level and unlock the chest on the left to find an art gallery pamphlet featuring Amelia's work. </li>

            <p>richard croft study - part 2</p>
            <li>Lara's handprint cast in clay.</li>
            <li>A manuscript handwritten by Lara's father.</li>
            <li>A blank letter with accordion folds. </li>

            <p>main hall lower level - part 2</p>
            <li>The blank letter revealed counts as relic #44.</li>

            <p>secret vault</p>
            <li>The missing page from the renovation blueprints you found earlier, sitting on the counter in the far left corner. </li>
            <li>A jade dragon statue on the worktable in the middle of the room.</li>
            <li>A Tibetan scroll, also on the center table. </li>
            <li>The CROWBAR, in a metal box also on the worktable.</li>
            <li>Lord Croft's Codex, an elaborately bound book with the family crest on the front, sitting on the counter below the whiteboard with the grid lines. </li>
            <li>A sun-shaped plaque recessed into the wall in the corner farthest from the entrance.</li>

            <p>crypt</p>
            <li>golden rose</li>

            <p>richard croft study - part 3</p>
            <li>After finishing the main game</li>
            <li>After finishing the main game</li>
            <li>After finishing the main game</li>
             
        </ol>

        <h5>documents</h5>
        <ol>
         <p class="fw-bold">Richard Croft's Study</p>
          <li>Letter Lara reads during the intro cutscene.</li>
          <li>An audio recording from Richard's diary on the desk.</li>
          <li>One of Amelia Croft's journals, sitting on the coffee table in the middle of the room.</li>

          <p class="fw-bold">East Wing Sitting Room</p>
          <li>Note from Lara: red leacher chair near fireplace</li>
          <li>Coffee table near laptop</li>

          <p class="fw-bold">Main Hall Lower Level</p>
          <li>One of Amelia's diary entries.</li>
          <li>On the table opposite the box that held the flashlight, pick up Lara's phone.</li>
          <li>Just around the corner, on a shelf near a desiccated potted palm. Letter from Atlas de Mornay,</li>
  
          <p>servant's passage</p>
          <li>Behind the door to the stairs</li>
          <li>Bottom of the stairs. One of Richard Croft's audio recordings.</li>
          <li>At the bottom of the stairs, sitting on a wooden crate. Letter from Atlas to Amelia.</li>

          <p>wine cellar</p>
          <li>Pass by the rolling cart for now and continue to the end of the main isle. A note from Winston to Lara's father, sitting on a wooden table near a green chair.</li>
          <li>Another of Amelia's journals.</li>
          <li>on one of the wooden shelves.</li>
          <li>Before entering the LIBRARY. One of Lord Croft's journals</li>

          <p>library</p>
          <li>One of Amelia's journals, on a rolling cart just ahead. </li>
          <li> A recording from Lara's father, sitting on a small table near the rolling cart </li>
          <li>A note Richard penned to himself titled "Clues," sitting on a box next to the desk.</li>
          <li>Another of Richard's diary recordings, on the corner of his desk.</li>

          <p>master bedroom</p>
          <li>In the corridor leading to the bedroom, there's a wooden cabinet containing another of Richard's recorded journals. </li>
         <li>One of Amelia's journals, sitting on the footstool at the end of the bed. </li>
          <li>Another of Richard's recordings in the cabinet to the left of the bed.</li>
          <li>Another of Richard's recordings in the armoire to the left of the bed.</li>

          <p>amelia's atelier</p>
          <li>Just before the doors to Amelia Croft's studio, there's a cabinet containing document #24, a letter from Winston to Lord Croft. </li>
          <li>Another of Amelia's journals, just inside on the left.</li>
          <li> Another journal entry on the shelf near Amelia's painting of her husband.</li>
          <li>The paintings themselves also count as a document, rather than a relic.</li>
          <li>This entry from Amelia's diary is at the top of the ladder on the right. </li>

          <p class="fw-bold">Richard Croft's Study - part 2</p>
          <li>In the safe</li>

          <p>east wing lower level</p>
          <li>A note from Winston to Lara, sitting on a metal cart.</li>

          <p>secret vault</p>
          <li>Another entry from Richard's diary in the cabinet just inside on the left. </li>
          <li>One of Amelia's journal entries, on the bookshelf to the right of the counter with the blueprints. </li>
          <li>Another of Richard's recorded diary entries, also on the center table.</li>
          <li>A letter from Atlas de Mornay to Richard Croft, on the counter near the codex.</li>

          <p>basement tunnels - part 2</p>
          <li>When you break through the wall of the vault, you emerge in the tunnels below the LIBRARY. Use the crowbar you just found to pry open the metal locker.</li>
          <li>Then head for the southeast corner of the WINE CELLAR to find the servants' dining area and 2 metal lockers,</li>

          <p>crypt</p>
          <li>Just before the main chamber on the left.</li>
          <li>At the sarcophagus.</li>

          <p>main hall</p>
          <li>After the cutscene and a brief credits sequence, we flash forward a few days. Lara discovers a letter near the entryway. </li>
          <li>As you explore further, Lara talks to herself about how this experience has altered her feelings about the manor. There's no physical item to find.</li>
         
        </ol>
        
        <h5>murals</h5>
        <ol>
          <li>Sir Lancelot's Armour - hallway outside office</li>
          <li>Sir Reginald's Armour - library</li>
        </ol>
      </div>

      <a href="#top" class="skiplink">Top</a>
  </div>
  
  
  
  <style>

    ol li {
      margin-bottom: 10px;
    }

    ol p {
      font-weight: bold;
      text-transform: capitalize;
    }

    ul li {
      text-transform: capitalize;
    }

    ul p {
      text-transform: capitalize;
      font-size: 12px;
    }
    
  </style>
  