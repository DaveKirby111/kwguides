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
      <li>M7-2-5 Operation Mako Reactor III = Backpack (acc 2)</li>
      <li>M7-2-6 Assessories Recall = Paralyzing Shock</li>
    </ul>
  </div>

 
  <a href="#top" class="skiplink">Top</a>
</div>

<style>

 
  
</style>
