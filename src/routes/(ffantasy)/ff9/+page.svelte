<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "final fantasy IX";
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

  <div class="d-flex justify-content-center">
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

  <div class="ragtime mb-5">
    <h4>Ragtime Mouse</h4>

    <p>
      The Ragtime Mouse is a creature that you can encounter out on the world
      map at various points in the game. The encounter begins similar to a
      regular battle on the world map however the music is different and, rather
      than fighting the Ragtime Mouse, it will ask you a true or false question.
      You attack either the Circle icon to answer true or the X icon to answer
      false.
    </p>

    <table class="table table-responsive">
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

  <div class="ramuh mb-5">
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

  <div class="stellazio mb-5">
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

  <div class="cards">
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
</style>
