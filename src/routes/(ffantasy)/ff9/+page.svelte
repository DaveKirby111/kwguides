<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "Final Fantasy IX";
  import Sections from "$lib/sections.svelte";

  const sections = [
    {
      name: "mods",
      link: "#mods",
    },

    {
      name: "guides",
      link: "#guides",
    },
  ];
</script>

<Sections {sections} />

<div id="mods" class="mods">
  <h2>mods</h2>

  <div class="d-flex div justify-content-center">
    <div class="me-5 text-center">
      <p>Memoria Engine</p>
      <p>
        <a
          href="https://www.nexusmods.com/finalfantasy9/mods/3?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>Memoria Save Editor</p>
      <p>
        <a
          href="https://forums.qhimm.com/index.php?topic=11494.0"
          target="_blank">Visit Site</a
        >
      </p>
    </div>
  </div>
</div>

<div id="guides" class="guides">
  <h2>guides</h2>

  <div class="guide-sections">
    <p class="fw-bold text-decoration-underline">Sections</p>
    <ul class="skip">
      <li><a href="#trophies">trophies</a></li>
      <li><a href="#ragtime">ragtime mouse</a></li>
      <li><a href="#ramuh">ramuh</a></li>
      <li><a href="#stellazio">stellazio</a></li>
      <li><a href="#cards">tetra master</a></li>
    </ul>
  </div>

  <div id="trophies">
    <h4>trophies</h4>
    <h5>100% completion</h5>
    <div class="d-flex">
      <div>
        <ul>
          <li>heroes of gaia</li>
          <p>Collect all trophies.</p>
          <li>bloodlust</li>
          <p>Defeat 10000 enemies.</p>
          <li>Driving the Hard Bargain</li>
          <p>Purchase all items available from Stiltzkin.</p>
          <li>cracking the code</li>
          <p>Uncover the secret of the Eidolon Wall.</p>
          <li>one nag too many</li>
          <p>Cause Moguo to have a tantrum.</p>
          <li>follow your nose</li>
          <p>Raise your chocobo's beak level to 99.</p>
          <li>beach bum</li>
          <p>Visit every beach in Gaia.</p>
          <li>diggin' it</li>
          <p>Locate all hidden treasures on the world map.</p>
          <li>back online</li>
          <p>Repair the machine at Mognet Central.</p>
          <li>well lubricated</li>
          <p>Obtain a bottle of Superslick.</p>
          <li>frog wrangler</li>
          <p>Successfully catch 99 frogs.</p>
          <li>going for the gold</li>
          <p>Successfully catch a golden frog.</p>
          <li>auctioneer</li>
          <p>Win 10 items at the Treno Auction House.</p>
          <li>sword of kings</li>
          <p>Obtain the sacred blade Excalibur.</p>
          <li>Beating the Ragtime Blues</li>
          <p>Correctly answer all the questions in Ragtime Mouse's pop quiz.</p>
          <li>mister nice guy</li>
          <p>Gain the favor of all friendly enemies.</p>
          <li>to ozma and back</li>
          <p>Defeat Ozma.</p>
          <li>my little airship</li>
          <p>Obtain a miniature copy of the Prima Vista.</p>
          <li>Earning the Queen's Favor</li>
          <p>Receive 10 rewards from Queen Stella.</p>
          <li>What's Your Sign?</li>
          <p>Obtain the Hammer.</p>
          <li>Another Man's Treasure</li>
          <p>Receive certification as a Rank S Treasure Hunter.</p>
          <li>The Ultimate Flute</li>
          <p>Obtain the Angel Flute.</p>
          <li>The Ultimate Mace</li>
          <p>Obtain the Mace of Zeus.</p>
          <li>The Ultimate fork</li>
          <p>Obtain the Gastro Fork.</p>
          <li>The Ultimate sword</li>
          <p>Obtain Excalibur II.</p>
          <li>The Ultimate rod</li>
          <p>Obtain the Whale Whisker.</p>
        </ul>
      </div>
      <div>
        <ul>
          <li>dragon lady</li>
          <p>Defeat Behemoth in the Treno weapon shop using Dagger.</p>
          <li>hail to the king</li>
          <p>Jump rope 1000 times without tripping and obtain King of Jump Rope.</p>
          <li>skip to my lou</li>
          <p>Jump rope 100 times without tripping.</p>
          <li>a round of applause</li>
          <p>Have the nobles demand an encore.</p>
          <li>A-Hunting We Will Go</li>
          <p>Win with Vivi during the Festival of the Hunt.</p>
          <li>All's Well That Ends Well</li>
          <p>Complete FINAL FANTASY IX.</p>
          <li>end of the road</li>
          <p>Attain level 99 with at least one character.</p>
          <li>the one ring</li>
          <p>Obtain Madain's Ring via mining.</p>
          <li>Peek-A-Boo</li>
          <p>Free Kuppo from a wall in Fossil Roo.</p>
          <li>track star</li>
          <p>Obtain Athlete Queen.</p>
          <li>found in the shuffle</li>
          <p>Beat the Nero Brothers' shuffling game nine times in a row.</p>
          <li>It's All in the Cards I</li>
          <p>Win a Tetra Master match.</p>
          <li>It's All in the Cards II</li>
          <p>Win 10 Tetra Master matches. </p>
          <li>It's All in the Cards III</li>
          <p>Win 100 Tetra Master matches. </p>
          <li>A Clean Bill of Health</li>
          <p>Have a single character affected by all status ailments (both beneficial and detrimental).</p>
          <li>Overly Emotional</li>
          <p>Enter trance 50 times.</p>
          <li>movie critic</li>
          <p>View 79 Active Time Events.</p>
          <li>over the moon</li>
          <p>Obtain 4 moonstones.</p>
          <li>kain's legacy</li>
          <p>Obtain Kain's Lance.</p>
          <li>Close But No Cigar</li>
          <p>Obtain the Tower.</p>
          <li>The Ultimate Claws</li>
          <p>Obtain the Rune Claws.</p>
          <li>The Ultimate racket</li>
          <p>Obtain the Tiger Racket.</p>
          <li>The Ultimate dual blade</li>
          <p>Obtain the Ultima Weapon.</p>
          <li>path of the samurai</li>
          <p>Obtain the complete set of Genji armor.</p>
          <li>your lucky day</li>
          <p>Receive a Very Good Omen from a color fortune.</p>
          <li>out of harm's way</li>
          <p>Guide all the residents of Cleyra to safety.</p>
        </ul>
      </div>
    </div>
  </div>

  <div class="ragtime mb-5" id="ragtime">
    <h4>Ragtime Mouse</h4>

    <p>
      The Ragtime Mouse is a creature that you can encounter out on the world
      map at various points in the game. The encounter begins similar to a
      regular battle on the world map however the music is different and, rather
      than fighting the Ragtime Mouse, it will ask you a true or false question.
      You attack either the Circle icon to answer true or the X icon to answer
      false.
    </p>

    <table class="table table-dark table-striped table-responsive">
      <thead>
        <tr>
          <th>Question</th>
          <th>Answer</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>The 15th Lindblum War started in 1600.</td>
          <td>False</td>
        </tr>
        <tr>
          <td>“I Want to Be Your Canary” was written by Lord Afon.</td>
          <td>False</td>
        </tr>
        <tr>
          <td>The theater ship Prima Vista was built in Artania Shipyards.</td>
          <td>False</td>
        </tr>
        <tr>
          <td>Chocobo’s Forest is located between Lindblum and South Gate.</td>
          <td>True</td>
        </tr>
        <tr>
          <td>Some Mus are friendly and won’t attack.</td>
          <td>True</td>
        </tr>
        <tr>
          <td>Berkmea Cable Cars have been running for eight years.</td>
          <td>True</td>
        </tr>
        <tr>
          <td>The theater ship Prima Vista uses Mist as its energy.</td>
          <td>True</td>
        </tr>
        <tr>
          <td>Lindblum Castle is larger than Alexandria Castle.</td>
          <td>True</td>
        </tr>
        <tr>
          <td>Lindblum’s air cabs operate around the clock.</td>
          <td>True</td>
        </tr>
        <tr>
          <td
            >Fossil Roo is an underground tunnel that connects Treno and
            Alexandria.</td
          >
          <td>False</td>
        </tr>
        <tr>
          <td>Prima Vista means love at first sight.</td>
          <td>False</td>
        </tr>
        <tr>
          <td>The Bobo bird is a bird that brings you fortune.</td>
          <td>False</td>
        </tr>
        <tr>
          <td>Only one desert exists in the entire world.</td>
          <td>False</td>
        </tr>
        <tr>
          <td>Treno’s cafe, Card Carta, is members-only.</td>
          <td>True</td>
        </tr>
        <tr>
          <td>Conde Petie is a village of Goblins.</td>
          <td>False</td>
        </tr>
        <tr>
          <td>You can defeat Ragtimer</td>
          <td>True</td>
        </tr>
      </tbody>
    </table>
  </div>

  <div class="ramuh mb-5" id="ramuh">
    <h4>Pinnacle Rocks and Ramuh</h4>

    <p>
      Ramuh will ask you to recite the story back to him which can be done in
      the following order:
    </p>

    <ul>
      <li>Beginning</li>
      <li>Cooperation</li>
      <li>Silence</li>
      <li>Human or Hero</li>
    </ul>
  </div>

  <div class="stellazio mb-5" id="stellazio">
    <h4 class="mb-5">stellazio</h4>

    <div class="d-flex">
      <div>
        <ul>
          <li>Aries = Village of Dali, inside windmill</li>
          <li>Cancer = Entrance of Burmecia, behind wooden box</li>
          <li>Scorpio = Quan's Dwelling, near pool after climbing down rope</li>
          <li>Gemini = Treno fountain, Throw 10 gil 13 times</li>
          <li>Taurus = item shop stall in Treno (Garnet section)</li>
          <li>Virgo = Black Mage Village, near beds in the inn</li>
          <li>Libra = Madain Sari, behind fountain</li>
          <li>Leo = Alexandria Castle, near Neptune Statue</li>
          <li>
            Sagittarius = Lindblum, Business District, left side from the cart
          </li>
          <li>Capricorn = Daguerro, right side of main hall</li>
          <li>Aquarius = Ipsen's Castle</li>
          <li>Pisces = Invincible Airship, chest</li>
          <li>
            Ophiucus = can only be found once all others have been obtained.
            Same place as Scorpio.
          </li>
        </ul>
      </div>

      <div>
        <p class="fw-bold">Rewards:</p>

        <ol>
          <li>1,000 gil</li>
          <li>Phoenix Pinion</li>
          <li>2,000 gil</li>
          <li>Blood Sword</li>
          <li>5,000 gil</li>
          <li>Elixir</li>
          <li>10,000 gil</li>
          <li>Black Belt</li>
          <li>20,000 gil</li>
          <li>Rosetta Ring</li>
          <li>30,000 gil</li>
          <li>Robe of Lords</li>
          <li>Hammer</li>
        </ol>
      </div>
    </div>
  </div>

  <div class="cards" id="cards">
    <h4 class="mb-5">Tetra Master</h4>

    <p>
      The game grid has 16 squares with up to 6 of those squares randomly locked
      off from being used. Each player takes turns placing a card on the game
      grid until all of the cards have been played. The object of the game is to
      challenge or battle adjacent cards and “capture” them over to your color.
    </p>

    <p class="fw-bold">Card Values</p>

    <ul>
      <li>The first character represents the power of the card</li>
      <li>The second character represents the class of the card</li>
      <li>The third character represents the physical defense of the card</li>
      <li>The fourth character represents the magical defense of the card</li>
    </ul>

    <p>
      The character/value is represented via hexadecimal, which means that the
      value will range (from lowest to highest) as shown: 0, 1, 2, 3, 4, 5, 6,
      7, 8, 9, A, B, C, D, E, F
    </p>

    <p>
      The first character is the Power Stat. It represents the offensive power
      of the card and the power that the card has when it is used to attack and
      capture other cards on the board.
    </p>

    <p>
      The second character is the Card’s Class which will be represented as
      either:
    </p>

    <ul>
      <li>P = physical</li>
      <li>M = magical</li>
      <li>X = flexible</li>
      <li>A = assault</li>
    </ul>

    <p>
      Having a P class means that the card’s attack will impact the physical
      defense, M means it will attack the magical defense, X will attack the
      lowest of the two stats (and this is an extremely rare class), and A will
      attack the lowest overall value on the card.
    </p>

    <p>
      The arrows on the card, pointing either up, left, down, right or to any of
      the corners, indicate the direction of attack that the card will employ.
      No arrow pointing on the card means that the card will not attack any
      adjacent cards in those directions.
    </p>

    <p class="fw-bold">Strategies</p>

    <p>
      Make sure that you protect your cards by placing them in secure locations
      using the blocks placed around the board. Save your stronger cards for the
      end of the game making sure that the arrow directions will allow you to
      utilize it properly when the time comes and then unleash it for a final
      combo.
    </p>
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<style>
  .stellazio div {
    justify-content: center;
  }

  ul li {
      text-transform: capitalize;
    }

    ul p {
      text-transform: capitalize;
      font-size: 12px;
    }

  @media screen and (max-width: 600px) {
    div {
      padding: 5px;
    }
  }
</style>
