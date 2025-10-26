<script>
    
    import { pageTitle } from "$lib/stores.js";
    pageTitle.set("Baldur's Gate 3");
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

      <div>
        <h3>items of interest</h3>
        <div class="items">
         <div>
          <h5>Spaceshunt Boots</h5>
          <p><b>Special:</b> Dimension Door</p>
          <p><b>Location:</b> Dropped by Dolor during <b style="color: yellow;">Investigate the temple murders</b></p>
        </div>
        <div>
          <h5>Warped Headband of Intellect</h5>
          <p><b>Special:</b> Set wearers Intelligence to 17</p>
          <p><b>Location:</b> Dropped by Lump the Enlightened in the Blighted Village</p>
        </div>
        <div>
          <h5>Gloves of Dexterity</h5>
          <p><b>Special:</b> Set wearers Dexterity to 18, Attack rolls +1</p>
          <p><b>Location:</b> Purchase at the Githyanki Creche</p>
        </div>
         </div>
      </div>

      <div>
        <h3>infernal iron</h3>
  
        
          <h5>act 1</h5>
          <ol>
            <li>Blighted Village- inside a chest in the forge basement</li>
            <li>Goblin Camp- behind a locked gate in the room with Dror Ragzlin</li>
            <li>Zhentarim Basement- in a trapped chest</li>
            <li>Grymforge- Stonemason Kith</li>
          </ol>
         
            <h5>act 2</h5>
          <ol>
            <li>Reithwin Mason's Guild</li>
            <li>Gauntlet of Shar- Opulent chest in room near Balthazar</li>
            <li>Gauntlet of Shar- carried by Yurgir</li>
          </ol>
         
          <h5>act 3</h5>
          <ol>
            <li>Flymm Cargo's Basement- on the floor</li>
            <li>carried by Steel Watchers</li>
            <li>Iron Throne- on a table in the dock</li>
            <li>Sold by Huido at the docks</li>
          </ol>
         
       
      </div>

      <div>
        <h3>strategies</h3>
        <div>
          <h5>Moonrise Towers</h5>
          <p>You can make friends with the Knolls by passing a persuasion check.</p>
          <p>Can convince the Duergar to get rid of the recruits.</p>
          <p>Kill the warden down in the prison</p>
          <p>Kill Z'rell and the scrying eye on the second floor.</p>
          <p>- OR -</p>
          <p>You can go up the left side from the bridge to the second floor. You end up outside Balthazar's room. This will skip the fight down below.</p>
        </div>
        <div>
          <h5>balthazar</h5>
          <p>In the Gauntlet of Shar, from the entrance and facing into the gauntlet, to the left and up the stairs is a sarcophygus. Behind it is a path with mushrooms and a door below. The door leads to the room with Balthazar. Using a character with Misty Step, invisibility and Knock, you can unlock the door which will trigger the fight. Have that character leave and escape the battle. You can then wait while Balthazar is killed by the spawning undead.</p>
        </div>
        <div>
          <h5>nere</h5>
          <p>An easy way to get Nere's head is to fast travel or rest a couple of times while he dies from being trapped.</p>
          <p>You can also convince Elder Brithvar to side against Nere.</p>
          <p>Philomeen, and the Runpowder Vial, is through the double doors on the eastern side of the docks. Up the stairs and past the Ochre Jellies.</p>
        </div>
        <div>
          <h5>Thisobald Thorm (Bartender)</h5>
          <p>He can be killed through dialogue options:</p>
          <ol>
            <li>What are you serving?</li>
            <li>pick up tankard</li>
            <li>[Sleight of Hand] mime drinking</li>
            <li>[Performance] tell a story</li>
            <li>ask questions</li>
            <li>[Sleight of Hand] mime drinking</li>
            <li>[Performance] tell a story</li>
            <li>ask questions</li>
            <li>[Sleight of Hand] mime drinking</li>
          </ol>
        </div>
        <div>
          <h5>Gerringothe Thorm (Tollhouse Boss)</h5>
          <p>Can be killed through dialogue:</p>
          <ol>
            <li>What do you require?</li>
            <li>If I give you gold, what do I get in return?</li>
            <li>Toss a gold piece</li>
            <li>I don't hand out gold for so little in return.</li>
            <li>[Persuasion] take gold and be free.</li>
            <li>[Persuasion] there is no one to overse you. - OR -</li>
            <li>[Deception] you are the new toll collector.</li>
          </ol>
        </div>
        <div>
          <h5>Malus Thorm (House of Healing)</h5>
          <p>Can be killed through dialogue:</p>
          <ol>
            <li>A student, yes.</li>
            <li>[Investigation] examine the sisters and their implements.</li>
            <li>[Persuasion] the sisters aren't ready. They will make me sick instead of curing me.</li>
            <li>[Persuasion] hone their skills on each other.</li>
            <li>[Persuasion] - or - [Deception] have him show you.</li>
          </ol>
        </div>
        <div>
          <h5>Yurgir (Gauntlet of Shar)</h5>
          <p>Can be killed through dialogue:</p>
          <ol>
           <li>tell him you just want to talk</li>
           <li>you know Raphael?</li>
           <li>say the you have also had dealings with Raphael</li>
           <li>share your experiences</li>
           <li>Show me this contract...</li>
           <li>your contract is a song?</li>
           <li>[Persuasion] the lyrics are a trick.</li>
           <li>[Persuasion] the displacer</li>
           <li>[Persuasion] have him kill himself</li>
          </ol>
        </div>
        <div>
          <h5>Ketheric Thorm (fight 1)</h5>
          <p>First, you need to get the letter from his wife. It is in a locked chest in his room.</p>
          <ol>
            <li>[Persuasion] Melodia wanted more for you than this.</li>
            <li>Melodia is waiting for you.</li>
            <li>I can help you...</li>
          </ol>
          <h5>Ketheric Thorm (fight 2)</h5>
          <ol>
            <li>I want to be free of the tadpole</li>
            <li>[Persuasion] I was ready to spare you before</li>
          </ol>
        </div>
      </div>

      <a href="#top" class="skiplink">Top</a>
  </div>
  
  
  
  <style>
    .items {
      display: flex;
    }
    
    .items div {
      width: 33.3%;
    }
  </style>
  