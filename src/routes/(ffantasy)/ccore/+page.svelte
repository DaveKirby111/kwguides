<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "Final Fantasy VII: Crisis Core";
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
      <li><a href="#clubs">fan clubs</a></li>
      <li><a href="#slots">accessory slots</a></li>
      <li><a href="#banora">banora treasure</a></li>
      <li><a href="#wonders">seven wonders</a></li>
    </ul>
  </div>

  <div id="clubs">
    <h4>fan clubs</h4>

    <h5>club 1 - red leather, Genesis fan</h5>
    <p>Chapter 2 = group of 3 women by the plaza fountain</p>

    <h5>club 2 - keepers of honor, Angeal fan</h5>
    <p>Chapter 2 = same group of women</p>

    <h5>club 3 - loveless study group</h5>
    <p>Chapter 2 = Loveless Avenue, by theater</p>

    <h5>club 4 - silver elite</h5>
    <p>Chapter 5 = Sephiroth fan in sector 6 slums park</p>
    <ol>
      <li>Question 1: Masamune</li>
      <li>Question 2: Super Nova</li>
      <li>Question 3: Left hand</li>
    </ol>

    <h5>club 5 - Zack fan club</h5>
    <p>Chapter 6 and 7 = As a prerequisite you must speak to Cissnei in Chapter 6. The story will bring you to a road where a minigame takes place to kill as many enemies as possible (enemy counter in top left corner, the “Immovable Object” trophy takes place here and you have to defend the gate at the end of the road). After the enemies are defeated, get on the elevator on the side of the road, it will be marked by a golden “!” icon on the map, BEFORE entering Junon Airport.</p>

    <p>If you did the above, then in Chapter 7 you can speak to the Receptionist in Shinra Building Entrance to join this Fan Club. The receptionist sits behind the receptionist’s deck on the ground floor of Shinra Building, the hall where you enter when coming from the Fountain area.</p>

    <h4>unite all fan clubs</h4>
    <p>You can unite all Fan Clubs in Chapter 7 for trophy Fan Club Savior trophy / achievement (helped every fan club continue their activities).</p>
    <ol>
      <li>Speak to the Genesis Fan in Sector 8 – Fountain, and suggest merging with a richer club.</li>
      <li>Head into LOVELESS Avenue and speak with the Genesis Fan there. Return to the first Genesis Fan at The Fountain and talk to her again.</li>
      <li>For the Angeal Fan Club, speak to the child in Sector 8 – Fountain who is looking for his mother. Then head up to Sector 1 – Train Station and speak to the mother, and select the “mother without honor” option. Then return to where the boy was and speak to the mother again. The Fan Club Savior trophy will unlock after this.</li>
    </ol>
  </div>

  <div class="acc" id="slots">
    <h4>additional accessory slots</h4>

    <p>Reach Chapter 4: An Angel's Dream</p>

    <p>Need M7-2 mission chain</p>
    <ul>
      <li>M7-2-1 Search and Destroy = Item Fusion Tome</li>
      <li>M7-2-2 Search and Destroy II = Keychain (acc 1)</li>
      <li>M7-2-3 Operation Mako Reactor I = Thunder Armlet</li>
      <li>M7-2-4 Operation Mako Reactor II = Dragon Armlet</li>
      <li>M7-2-5 Operation Mako Reactor III = Backpack (acc 2ç)</li>
      <li>M7-2-6 Assessories Recall = Paralyzing Shock</li>
    </ul>
  </div>

  <div class="banora" id="banora">
    <h4>banora treasure</h4>

    <p>From where you start, grab the fourth, then take a detour to grab the fifth, then the second, third, and first. If all goes well, you should have about ten seconds to make it back to Angeal’s house, which is more than enough time.</p>

    <ol>
      <li>As you enter the area near Angeal’s house, to your left. It sits at the side of another house that, if you knock on the door, will start a battle.</li>
      <li>Next to the water well in that same area.</li>
      <li>Beside the storage of logs and barrels next to the house furthest from the area entrance.</li>
      <li>Further down the path, next to a gathering of crates and barrels.</li>
      <li>Even further down the path, next to some rocks overlooking the enemy warehouse.</li>
    </ol>
  </div>

  <div class="seven" id="wonders">
    <h4>seven wonders</h4>

    <ol>
      <li><p>Beginning the Seven Wonders of Nibelheim side quest requires Zack to approach the young boy standing in the center of the town, across from the water tower. The child will then explain to Zack that Nibelheim is home to some strange phenomena before asking the SOLDIER to investigate them.</p>
      
      <p>Zack must climb to the top of the water tower and remove the Summon Materia from the well. Not only will removing the Materia satisfy the young boy's interest in the First Wonder, but it will also grant Zack access to the Phoenix summon. After speaking to the boy again, Zack can then begin his search for the Second Wonder.</p></li>

      <li><p>The boy isn't overly excited about Zack's findings and instead asks the SOLDIER to investigate the portrait on the second floor of the inn. Supposedly, the woman depicted in the portrait has a habit of disappearing, but the only way to see this is to check the portrait a few times.</p>
      
      <p>Upon examining the portrait, Zack can then return to the boy to report his findings. Then, he must examine the portrait again, where he will discover that the woman depicted has vanished. The portrait will continue to change whenever Zack leaves the second floor.</p>
    
    <p>Eventually, the man standing behind the desk will walk up the stairs and sprint to the portrait. When approached, the man will reveal what the Second Wonder actually is. To begin the hunt for the Third Wonder, Zack must speak to the boy.</p></li>

      <li><p>The next wonder of Nibelheim can only be found by traveling through the Nibelheim - Outskirts and entering the Mt. Nibel - Trail. According to the boy, there's an unusual bomb wandering the mountain path that drops a rare item when it's defeated. To test this theory, Zack must follow the path to the east into the dead end.</p>
      
      <p>There, he will be greeted by three Bombs, each of whom must be defeated before they explode. Once they have been vanquished and the Gold Shard has been obtained, returning to the boy standing beside the water tower will begin the search for the Fourth Wonder.</p></li>

      <li><p>To solve the mystery of the Fourth Wonder, Zack must head to the Shinra Mansion located to the west in the Nibelheim - Outskirts. Rumors of a "laughing safe" have been circulating around the town, so Zack must find the combination for said safe in order to uncover who's behind it.</p>
      
      <p>Sadly, the combination changes depending on the playthrough, so players will need to solve this puzzle all by themselves. To require the four-digit code for the safe, Zack must peek through the four sealed doors in the Shinra Mansion. Then, the player will need to count whatever notable items or creatures they see.</p>
    
    <h5>The First Laughing Safe Digit</h5>
  
  <p>To learn the first digit, the player must peek through the eastern door on the second floor and count all the books that have been left lying around the room. The books on the floor, the books on the chair, and the books on top of the bookcase must all be counted to learn the laughing safe's first digit.</p></li>

  <h5>The Second Laughing Safe Digit</h5>
  <p>On the first floor, while peeking through the eastern door, the player will need to count the monsters they see to learn the second digit. Some monsters can drift out of view, so the player should be sure to thoroughly investigate the far corners of the room before deciding on a digit.</p>

  <h5>The Third Laughing Safe Digit</h5>
  <p>Outside the safe room, while looking to the west, Zack will come across the door containing the third digit. While looking through the keyhole, the player must count each Banora Apple present in the room. To make matters even more difficult, the cans spread around the room must also be counted in order to learn the third digit.</p>

  <h5>The Fourth Laughing Safe Digit</h5>
  <p>The fourth and final digit can then be found on the first floor by looking through the western door. The player must count how many chairs are located behind this sealed door in order to complete the combination. When all four digits have been obtained, the player can return to the laughing safe to open it. Once the Fourth Wonder has been unearthed, Zack must report his findings to the boy.</p>

      <li><p>Finding the Fifth Wonder of Nibelheim requires the player to visit the Shinra Mansion, but only after visiting the Mako Reactor and returning to town with Cloud and Tifa. Upon reaching the mansion with Cloud, Zack will be able to use the previously inoperable lift to descend into the cave system below.</p>
      
      <p>There, he will need to slay a few Sahagin groups to obtain keys to open the coffins located behind the two red doors. Bizarre Bugs are waiting to attack within three of these coffins, but the coffin on the right-hand side inside the eastern room contains the supposed Fifth Wonder of Nibelheim. Once it has been discovered, Zack should return to the boy beside the water tower, as continuing with the story will prevent the quest from being completed.</p></li>

      <li><p>The boy will reveal that the Sixth Wonder is known as "the treasure within the flames," but sadly, he doesn't know anything else about it. To discover what this Wonder is, the player must continue playing through the story until they meet the boy again. His mother is trapped in a burning house, so Zack must enter inside, figure out the house's layout, and exit the premises within the given time limit.</p>
      
      <p>Though it can be difficult to find the correct route, the best way to reach the boy's mother is to walk to the right side of the house, push forward to the back, continue left up the stairs, walk toward the camera, and then proceed right. There, Zack will locate the mother. To escape, he must then backtrack the way he came. Once she has been saved, the boy will realize his mother was the Sixth Wonder of Nibelheim.</p></li>

      <li><p>Though the boy tries to discuss the Seventh Wonder of Nibelheim immediately after his mother's near-death experience, Zack informs him that it "can wait." To finish this side quest, the player must continue the story until Zack escapes the Shinra Mansion during the next chapter.</p>
      
      <p>Upon walking away from the mansion, the boy will send Zack a mail informing him that he left a gift for him somewhere in the Nibelheim - Outskirts. While he suggests that Nibelheim itself can be considered the Seventh Wonder, most players will prefer the gift the boy left behind.</p>
    
    <p>To find this gift, Zack must follow the northeastern path to the top of the Nibelheim - Outskirts and then proceed south. Located just behind the fence next to the furthest house will be a Wall Materia, one of the best defensive Materia in all of Crisis Core: Final Fantasy 7 Reunion. Once it has been collected, the Wonders of Nibelheim quest will end.</p></li>
    </ol>
  </div>

 
  <a href="#top" class="skiplink">Top</a>
</div>

<style>

 
  
</style>
