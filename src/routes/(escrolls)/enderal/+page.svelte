<script>
  import { pageTitle } from "$lib/stores.js";
  pageTitle.set("Enderal");
  import Sections from "$lib/sections.svelte";

  // const sections = [
  //   {
  //     name: "console commands",
  //     link: "#console",
  //   },

  //   {
  //     name: "guides",
  //     link: "#guides",
  //   },
  // ];

  const commands = [
    {
      name: "god mode",
      input: "tgm",
      desc: "toggle god mode. Infinite health, magicka, fatigue",
    },

    {
      name: "money",
      input: "player.additem f (amount)",
      desc: "give the player gold",
    },

    {
      name: "lockpicks",
      input: "player.additem a (amount)",
      desc: "give the player lockpicks",
    },

    {
      name: "memory points",
      input: "set talentpoints to {Number of points wanted}",
      desc: "give memory points",
    },

    {
      name: "map markers",
      input: "tmm (1 or 0)",
      desc: "toggle map markers",
    },
  ];
</script>

<!-- <Sections {sections} /> -->

<div class="intro">
  <h4>intro</h4>

  <h5>what is enderal</h5>

  <p>
    Enderal is a total conversion mod for the Elder Scrolls V: Skyrim. It
    contains it's own world and lore but it runs on Skyrim's engine and uses
    mechanics, items, and features from Skyrim. It is even dependant on the user
    owning a copy of Skyrim in order to play it. It is however, listed on Steam
    as being it's own game. Because it is so dependant on Skyrim I am treating
    it as a mod rather than it's own game, and putting it under the Elder
    Scrolls title.
  </p>
</div>

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
      <li><a href="#trophies">trophies</a></li>
      <li><a href="#armor">armor</a></li>
      <li><a href="#recipes">recipes</a></li>
    </ul>
  </div>

  <div id="trophies">
    <h4>trophies</h4>
    <h5>100% completion</h5>
    <div class="d-flex">
      <ul>
        <li>a better world</li>
        <p>You chose to flee to the Starcity.</p>
        <li>a fine drink</li>
        <p>You shared a drink with Lishari Peghast.</p>
        <li>a sliver of hope</li>
        <p>You found the Beacon.</p>
        <li>adventurous</li>
        <p>Complete 50 quests</p>
        <li>Aren't we beautiful?</li>
        <p>
          You relived another version of your nightmare. Aren't we beautiful?
        </p>
        <li>behind the horizon</li>
        <p>You discovered 50 different locations.</p>
        <li>bounty hunter</li>
        <p>You finished all bounty quests.</p>
        <li>burnt flesh</li>
        <p>You relived your nightmare.</p>
        <li>card shark</li>
        <p>You won 10 rounds of "Battle for Treomar."</p>
        <li>Catch 'Em All</li>
        <p>found all souls</p>
        <li>Chronicles of Blood</li>
        <p>You found and read all books of the Butcher.</p>
        <li>claws</li>
        <p>You brewed and drank your first Wolf's Blood potion.</p>
        <li>Come On, You Stupid Rod</li>
        <p>
          You found a brave warrior's frozen corpse in the Frostcliff Mountains.
        </p>
        <li>cosmic harmony</li>
        <p>You let the Master Skull harmonize your chakras. Namaste!</p>
        <li>Coup De Grace</li>
        <p>
          You killed Mirell's daughter so that the Red Madness doesn't spread.
        </p>
        <li>crunchy pleasures</li>
        <p>You tasted a slice of Marita Rotang's fresh, tasty bread.</p>
        <li>Cuthbert the Spirit Pig</li>
        <p>You summoned the spirit of Cuthbert the minipig.</p>
        <li>dice god</li>
        <p>You won 10 rounds of "Morala's Dice."</p>
        <li>direwolf</li>
        <p>You found the Father's hidden gift.</p>
        <li>fetchquest</li>
        <p>You found all of Enderal's magical symbols.</p>
        <li>fetchquest vol. 2</li>
        <p>You found all of Enderal's mystical symbols.</p>
      </ul>
      <ul>
        <li>finders keepers</li>
        <p>You lied to Maél Dal'Loran about the origin of the trinket.</p>
        <li>free at last</li>
        <p>You sacrificed yourself to give mankind another chance.</p>
        <li>gertrude's wings</li>
        <p>You found Kurmai's pride - Gertrude the Starship.</p>
        <li>goldrush</li>
        <p>mined 50 ore veins</p>
        <li>good shot</li>
        <p>You scored well in Rynéus starling-sphere game.</p>
        <li>Goodbye, Daddy</li>
        <p>You relived the third version of your nightmare.</p>
        <li>halfmoon island</li>
        <p>You took the Pyrean train to Halfmoon Island.</p>
        <li>He Already Paid the Price</li>
        <p>You disapproved of Tharaêl killing Qalian.</p>
        <li>hidden powers</li>
        <p>You found and read a hidden talent book.</p>
        <li>Home, Sweet Home</li>
        <p>You bought yourself a home in Ark.</p>
        <li>icy embrace</li>
        <p>You froze and shattered an enemy.</p>
        <li>invasion</li>
        <p>You rebutted the Nehrimese's attack on Ark.</p>
        <li>Keeper of the Holy Order</li>
        <p>You became a Keeper of the Holy Order.</p>
        <li>knowledge is power</li>
        <p>You found and earned all knowledge points.</p>
        <li>lethonia</li>
        <p>You won Jespar Dal'Varek's heart.</p>
        <li>legendary</li>
        <p>You combined two synergetic classes and unlocked an affinity.</p>
        <li>Lyrical Outpours and Other Bodily Fluids</li>
        <p>You read an analysis of Prince Mith's poetry.</p>
        <li>mage-bane</li>
        <p>You died from Arcanist's fever.</p>
        <li>mammon</li>
        <p>
          accumulated 100,000 Endralean penny coins and entrusted them to Samael
          Silren.
        </p>
        <li>master of eggs</li>
        <p>You actually hunted down all eggs for Kurmai. Hats off.</p>
      </ul>
    </div>
    <div class="d-flex">
      <ul>
        <li>master of the arcane</li>
        <p>learned a mythical spell</p>
        <li>Music of the Lightborn</li>
        <p>You constructed the Koppophon.</p>
        <li>mythical</li>
        <p>unlock a second affinity</p>
        <li>Näea</li>
        <p>
          You followed Yuslan to his house in the alternate reality and
          witnessed a conversation.
        </p>
        <li>nifty</li>
        <p>
          Thanks to your sleight of hand, you found a big hidden slot in a
          chest.
        </p>
        <li>nimble feet</li>
        <p>You tricked the Starling lock mechanism on your first try.</p>
        <li>one soul</li>
        <p>You finished Calia's companion quest.</p>
        <li>onyx</li>
        <p>
          You found all three of the Black Stones and brought them to Lexil.
        </p>
        <li>part of something</li>
        <p>You finished Jespar's companion quest.</p>
        <li>philistine</li>
        <p>
          You engaged in a profound discussion about art and poetry with Prince
          Mith.
        </p>
        <li>proficient</li>
        <p>mastered a memory tree</p>
        <li>protector</li>
        <p>became a Protector</p>
        <li>reach for the stars</li>
        <p>You climbed Enderal's highest mountain. Congratulations!</p>
        <li>Rememberance</li>
        <p>Esme trusted you enough to reach out to you.</p>
        <li>repentance</li>
        <p>You prevented Tharael's suicide and gave him back hope.</p>
        <li>slayer of beasts</li>
        <p>You found and slayed all mythical beasts.</p>
        <li>Sleep, My Child</li>
        <p>You convinced Mirell to ease his daughter's suffering.</p>
        <li>steadfast</li>
        <p>Burn bridges with both Maél and Dijaam.</p>
        <li>synergetic</li>
        <p>You discovered a synergy between two talents.</p>
        <li>the beast overcome</li>
        <p>You won Calia Sakaresh's heart.</p>
        <li>the black guardian</li>
        <p>You realized that not all myths are just myths.</p>
      </ul>
      <ul>
        <li>the dreamflower</li>
        <p>You found, created and drank the Dreamflower potion.</p>
        <li>the grove</li>
        <p>Listened to the story of Silvergrove.</p>
        <li>the lion's roar</li>
        <p>
          You sided with Maél Dal'Loran in the conflict about the Scarabeus.
        </p>
        <li>the price of sin</li>
        <p>You approved of Tharaêl killing Qalian.</p>
        <li>The Queen of the Forsaken</li>
        <p>You opened Vatyra's treasure chamber.</p>
        <li>The Scorpion's Tail</li>
        <p>You sided with Dijaam in the conflict about the Scarabeus.</p>
        <li>The Spectral Horde</li>
        <p>You bound a lost soul into a Phasmalist's trinket.</p>
        <li>The Treasures of the Destitute</li>
        <p>You found all hidden stashes in the orphanage.</p>
        <li>There's Always Hope</li>
        <p>You gave Mirell hope.</p>
        <li>thorough</li>
        <p>You collected 15 butterflies for Rynéus.</p>
        <li>Vanquisher of Horst</li>
        <p>You neutralized Pathira, who took control of Yerai's centurion.</p>
        <li>voices of the dead</li>
        <p>You found and returned the Word of the Dead.</p>
        <li>well-equipped</li>
        <p>You acquired and wore a complete set.</p>
        <li>we're sorry</li>
        <p>
          You suffered through Enderal's rendition of the arrow in the knee
          joke.
        </p>
        <li>What dreams may come</li>
        <p>You convinced Rynéus to disband the illusion of Silvergrove.</p>
        <li>what we deserve</li>
        <p>Found captain Rocio.</p>
        <li>What's reality, anyways?</li>
        <p>You unlocked the hidden ending.</p>
        <li>whirlwind</li>
        <p>You became friends with Whirlwind, the Donkey.</p>
        <li>wings</li>
        <p>You flew on a Myrad's back for [sic] twenty times.</p>
        <li>worth it</li>
        <p>You and Dijaam escaped and kept the Scarabeus for yourselves.</p>
        <li>Yes, We Got Them Too</li>
        <p>You defeated Enderal's only dragon.</p>
      </ul>
    </div>
  </div>

  <div id="armor">
    <h4>armor sets</h4>
    <div>
      <h5>wandering mage</h5>
      <ul>
        <li>
          <p class="fw-bold">Soul(body: 139a81)</p>
          <p>The Navigator, inside the Navigator's room of Agnod.</p>
          <p>
            Lying on a table near the Sun Fire, close to a massive chest, along
            with some potions and the Arcanist's Backpack blueprint.
          </p>
          <p>
            On The Experimenter boss, can be found on the highest floor of
            Fortress Rockwatch.
          </p>
          <p>On the Nehrimese Scientist, inside the King's of Old Hatolis.</p>
        </li>
        <li>
          <p class="fw-bold">Hand(hands: 77381)</p>
          <p>Soul Bed, on the boss Lost Fire Mage.</p>
          <p>
            Inside the Northcliff Hold, lying on the one of the table in the
            torture room.
          </p>
        </li>
        <li>
          <p class="fw-bold">Echo(boots: 7737f)</p>
          <p>On The Mechanist, inside the airship Agnod.</p>
          <p>On the Nehrimese Scientist, inside the King's of Old Hatolis.</p>
          <p>Inside an open chest on a plateau inside the Frostwater Chasm.</p>
          <p>On the Nehrimese Scientist, inside the King's of Old Hatolis.</p>
        </li>
        <li>
          <p class="fw-bold">Shadow(hood: 148a1b)</p>
          <p>
            On The Colossus, a more powerful magical contruct north of the
            Northwind Camp.
          </p>
          <p>On the troll Momog, Deep Digger's Hollow, supply shaft.</p>
        </li>
      </ul>
    </div>
  </div>

  <div id="recipes">
    <h4>potion recipes</h4>
    <div class="d-flex">
      <div>
        <h5>cure disease</h5>
        <ul>
          <li>blue dragonfly wing</li>
          <li>crab shell</li>
          <li>hawk feathers</li>
          <li>rat skin</li>
        </ul>
      </div>
      <div>
        <h5>healing</h5>
        <ul>
          <li>bird egg</li>
          <li>blue dragonfly wing</li>
          <li>blue malphas flower</li>
          <li>demon heart</li>
          <li>rat skin</li>
          <li>red russula</li>
          <li>sheer cap</li>
          <li>vatyr eyeball</li>
          <li>wheat</li>
          <li>yellow butterly wing</li>
        </ul>
      </div>
      <div>
        <h5>mana</h5>
        <ul>
          <li>aeterna ears</li>
          <li>artichoke</li>
          <li>date</li>
          <li>fire salts</li>
          <li>flour</li>
          <li>frost salts</li>
          <li>mana salt</li>
          <li>mora tapinella</li>
          <li>pearl</li>
          <li>red malphas flower</li>
          <li>root</li>
          <li>spicy grass</li>
          <li>spiddal cane</li>
          <li>sugar</li>
          <li>taproot</li>
        </ul>
      </div>
    </div>
    <div class="d-flex">
      <div>
        <h5>ambrosia</h5>
        <ul>
          <li>baldris root</li>
          <li>ghost wrapping</li>
          <li>nightshade</li>
          <li>peaceweed</li>
          <li>thistle</li>
        </ul>
      </div>
      <div>
        <h5>wolf blood</h5>
        <ul>
          <li>baldris root</li>
          <li>blue butterfly wing</li>
          <li>blue malphas flower</li>
          <li>bone meal</li>
          <li>fog sponge</li>
          <li>garlic</li>
        </ul>
      </div>
      <div>
        <h5>fortify one-handed</h5>
        <ul>
          <li>bear claw</li>
          <li>bird egg</li>
          <li>claw</li>
          <li>hanging moss</li>
          <li>hawk feathers</li>
          <li>salt root</li>
          <li>small pearl</li>
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

  #recipes .d-flex {
    justify-content: center;
  }
</style>
