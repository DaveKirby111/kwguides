<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "dragon age: origins";
  import Sections from "$lib/sections.svelte";

  import bridge1 from "$lib/images/dao/bridge1.jpg";
  import bridge2 from "$lib/images/dao/bridge2.jpg";
  import bridge3 from "$lib/images/dao/bridge3.jpg";

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

  <div class="text-center">
    <p>Skip the Fade</p>
    <a
      href="https://www.nexusmods.com/dragonage/mods/816"
      target="_blank"
      rel="noopener noreferrer">nexus page</a
    >
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<div id="guides" class="guides">
  <h2>guides</h2>

  <div class="gifts mb-5">
    <h4>gifts</h4>
    <p>Alistair Gifts</p>
    <table
      class="table table-dark table-striped table-bordered table-responsive"
    >
      <thead>
        <tr>
          <th>gift</th>
          <th>found in</th>
          <th>location</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>alistair's mother's amulet</td>
          <td>desk</td>
          <td>castle redcliff: main floor</td>
        </tr>
        <tr>
          <td>black runestone</td>
          <td>chest</td>
          <td>aeducan thaig</td>
        </tr>
        <tr>
          <td>duncan's shield</td>
          <td>armor stand</td>
          <td>market warehouse</td>
        </tr>
        <tr>
          <td>onyx demon statuette</td>
          <td>pile of bones</td>
          <td>east brecilian forest</td>
        </tr>
        <tr>
          <td>small carved statuette</td>
          <td>crate</td>
          <td>lothering</td>
        </tr>
        <tr>
          <td>stone dragon statuette</td>
          <td>chest</td>
          <td>castle redcliff: upper floor</td>
        </tr>
        <tr>
          <td>stone warrior statuette</td>
          <td>pile of dragon filth</td>
          <td>caverns (Haven)</td>
        </tr>
        <tr>
          <td>white runestone</td>
          <td>abomination</td>
          <td>third floor of circle tower</td>
        </tr>
      </tbody>
    </table>
    <p>Morrigan Gifts</p>
    <table
      class="table table-dark table-striped table-bordered table-responsive"
    >
      <thead>
        <tr>
          <th>gift</th>
          <th>found in</th>
          <th>location</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>black grimoire</td>
          <td>irving's quarters</td>
          <td>circle tower</td>
        </tr>
        <tr>
          <td>flemeth's grimoire</td>
          <td>chest</td>
          <td>flemeth's hut</td>
        </tr>
        <tr>
          <td>gold amulet</td>
          <td>garin</td>
          <td>orzammar commons</td>
        </tr>
        <tr>
          <td>golden demon pendant</td>
          <td>corpse</td>
          <td>urn of sacred ashes room</td>
        </tr>
        <tr>
          <td>golden mirror</td>
          <td>garin</td>
          <td>orzammar commons</td>
        </tr>
        <tr>
          <td>golden rope necklace</td>
          <td>barlin</td>
          <td>dane's refuge in lothering</td>
        </tr>
        <tr>
          <td>locket</td>
          <td>locked chest</td>
          <td>village store in haven</td>
        </tr>
        <tr>
          <td>silver brooch</td>
          <td>varathorn</td>
          <td>dalish camp</td>
        </tr>
        <tr>
          <td>silver chain</td>
          <td>vanity</td>
          <td>senior mage quarters in circle tower</td>
        </tr>
        <tr>
          <td>silver medallion</td>
          <td>dragon hoard</td>
          <td>upper level in elven ruins</td>
        </tr>
        <tr>
          <td>tribal necklace</td>
          <td>barrel</td>
          <td>top floor of tower of ishal</td>
        </tr>
      </tbody>
    </table>
    <p>Leliana Gifts</p>
    <table
      class="table table-dark table-striped table-bordered table-responsive"
    >
      <thead>
        <tr>
          <th>gift</th>
          <th>found in</th>
          <th>location</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>andraste's grace</td>
          <td>flower</td>
          <td
            >redcliff village, <br />
            west brecilian forest, <br />
            alienage</td
          >
        </tr>
        <tr>
          <td>bronze symbol of andraste</td>
          <td>chest</td>
          <td>lothering chantry</td>
        </tr>
        <tr>
          <td>chantry amulet</td>
          <td>templar's corpse</td>
          <td>senior mage quarters (circle tower)</td>
        </tr>
        <tr>
          <td>etched silver symbol</td>
          <td>ruck</td>
          <td>ortan thaig</td>
        </tr>
        <tr>
          <td>golden symbol of andraste</td>
          <td>legnar's store</td>
          <td>orzammar commons</td>
        </tr>
        <tr>
          <td>nug</td>
          <td>nug wrangler</td>
          <td>orzammar commons</td>
        </tr>
        <tr>
          <td>silver sword of mercy</td>
          <td>dwarven vendor</td>
          <td>random encounter</td>
        </tr>
        <tr>
          <td>steel symbol of andraste</td>
          <td>chest</td>
          <td>brother genitivi's home</td>
        </tr>
      </tbody>
    </table>
    <p>Sten Gifts</p>
    <table
      class="table table-dark table-striped table-bordered table-responsive"
    >
      <thead>
        <tr>
          <th>gift</th>
          <th>found in</th>
          <th>location</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>painting of a rebel queen</td>
          <td>dwarven merchant</td>
          <td>random encounter</td>
        </tr>
        <tr>
          <td>portrait of a goosegirl</td>
          <td>faryn</td>
          <td>frostback mountains</td>
        </tr>
        <tr>
          <td>silver framed still-life</td>
          <td>chest</td>
          <td>upper level of castle redcliff</td>
        </tr>
        <tr>
          <td>sten's sword</td>
          <td>faryn in frostback mountains</td>
          <td>dwyn in redcliff village</td>
        </tr>
        <tr>
          <td>totem</td>
          <td>chest</td>
          <td>caridan's cross</td>
        </tr>
        <tr>
          <td>water-stained portrait</td>
          <td>charred corpse</td>
          <td>senior mage quarters</td>
        </tr>
      </tbody>
    </table>
    <p>Wynne Gifts</p>
    <table
      class="table table-dark table-striped table-bordered table-responsive"
    >
      <thead>
        <tr>
          <th>gift</th>
          <th>found in</th>
          <th>location</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>discovering dragon's blood</td>
          <td>bookshelf</td>
          <td>ruined temple</td>
        </tr>
        <tr>
          <td>fancy scroll</td>
          <td>sarcophagus</td>
          <td>lower ruins</td>
        </tr>
        <tr>
          <td>tattered notebook</td>
          <td>dog</td>
          <td>random change he'll fetch it</td>
        </tr>
        <tr>
          <td>the guerrins of ferelden</td>
          <td>bookshelf</td>
          <td>upper level of castle redcliff</td>
        </tr>
        <tr>
          <td>rose of orlais</td>
          <td>pile of books</td>
          <td>senior mage quarters</td>
        </tr>
        <tr>
          <td>search for the true prophet</td>
          <td>locked chest</td>
          <td>shaperate in orzammar</td>
        </tr>
      </tbody>
    </table>
    <p>Zevran Gifts</p>
    <table
      class="table table-dark table-striped table-bordered table-responsive"
    >
      <thead>
        <tr>
          <th>gift</th>
          <th>found in</th>
          <th>location</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>antivan leather boots</td>
          <td>iron chest</td>
          <td>village store (Haven)</td>
        </tr>
        <tr>
          <td>dalish gloves</td>
          <td>chest</td>
          <td>west brecilian forest</td>
        </tr>
        <tr>
          <td>medium gold bar</td>
          <td>treasure pile</td>
          <td>arl of denerim's estate</td>
        </tr>
        <tr>
          <td>medium silver bar</td>
          <td>chest</td>
          <td>anvil of the void</td>
        </tr>
        <tr>
          <td>small gold bar</td>
          <td>charmed templar</td>
          <td>templar's quarters</td>
        </tr>
        <tr>
          <td>small silver bar</td>
          <td>inscribed chest</td>
          <td>haven chantry</td>
        </tr>
      </tbody>
    </table>
    <p>Oghren Gifts</p>
    <table
      class="table table-dark table-striped table-bordered table-responsive"
    >
      <thead>
        <tr>
          <th>gift</th>
          <th>found in</th>
          <th>location</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>alley king's flagon</td>
          <td>legnar's store</td>
          <td>orzammar</td>
        </tr>
        <tr>
          <td>chasind sack mead</td>
          <td>dusty scrolls</td>
          <td>ruined temple</td>
        </tr>
        <tr>
          <td>garblog's backcountry reserve</td>
          <td>dog</td>
          <td>random chance he'll fetch it</td>
        </tr>
        <tr>
          <td>golden scythe 4-90 black</td>
          <td>crate</td>
          <td>lothering</td>
        </tr>
        <tr>
          <td>legacy white shear</td>
          <td>sarcophagus</td>
          <td>lower ruins</td>
        </tr>
        <tr>
          <td>sun blonde vint-1</td>
          <td>vanity</td>
          <td>templar quarters (circle tower)</td>
        </tr>
      </tbody>
    </table>
  </div>

  <div class="romance mb-5">
    <h4>romance</h4>
    <div class="leliana mb-5">
      <h5>leliana</h5>

      <div class="d-flex">
        <div>
          <p>initial dialogue</p>
          <ul>
            <li>I'd like to talk</li>
            <li>what was someone like you doing in lothering's chantry</li>
            <li>you know, a beautifal charming woman</li>
            <li>those initiates can't have been more lovely</li>
          </ul>
        </div>
        <div>
          <p>post Marjolaine</p>
          <ul>
            <li>we need to talk</li>
            <li>are you feeling batter</li>
            <li>I think I know what you mean</li>
            <li>She was special to you wasn't she?</li>
            <li>I'm sorry it ended so badly</li>
            <li>Everyone changes unfortunaely</li>
            <li>I can only hope to one day...</li>
          </ul>
        </div>
        <div>
          <p>
            To seduce Leliana she has to be in love with you; which means
            approval has to be at 100.
          </p>
        </div>
      </div>

      <div>
        <p class="text-center">* Personal Quest *</p>
        <p>Her approval must be 25+</p>
        <ul>
          <li>Ask her about minstrels being spies</li>
          <li>Leave and come back to camp</li>
          <li>Talk to Leliana and she will admit to lieing</li>
        </ul>
        <p>
          The next random encounter should be assassins sent to kill her. After
          beating them, Leliana will suggest going to confront Marjoliane
        </p>
      </div>
    </div>
    <div class="morrigan">
      <h5>morrigan</h5>

      <div class="d-flex">
        <div>
          <p>
            Start by asking about her upgringing and powers. When she gives the
            line "Tis a curious thing..."
          </p>
          <ul>
            <li>What, is something wrong</li>
            <li>why would I do that</li>
            <li>Because I need you here</li>
            <li>I was hoping to be more than friends</li>
          </ul>
        </div>
        <div>
          <p>After killing Flemeth</p>
          <ul>
            <li>Flemeth is dead, you are free</li>
            <li>Yes, but I intend to keep it for myself</li>
            <li>What? That's it?</li>
            <li>What was that last bit again?</li>
          </ul>
        </div>
        <div>
          <p>
            To get Morrigan to invite you back to the tent, you have to be at
            50+ approval. She will not sleep with you if she is in love with
            you.
          </p>
        </div>
      </div>
      <div>
        <p class="text-center">* Personal Quest *</p>
        <p>
          Finding the Black Grimoire in the circle tower and gifting it to
          Morrigan will begin her personal quest. Talking to her in camp will
          prompt her to send you to kill Flemeth. After killing her, Flemeth's
          Grimoire will be in her hut. Gift it to Morrigan.
        </p>
      </div>
    </div>
  </div>

  <div class="urn">
    <h4>urn of sacred ashes</h4>
    <h5>riddles:</h5>
    <p>Brona</p>
    <p>
      Riddle : Echoes from the shadow realm, whispers of things yet to come.
      Thought’s strange sister dwells in the night, is swept away by dawning
      light. Of what do I speak?
    </p>
    <p>Answer : Dreams</p>
    <hr />
    <p>Thane Shartan</p>
    <p>
      Riddle : I’d neither a guest nor a trespasser be; in this place I belong,
      that belongs also to me. Of what do I speak?
    </p>
    <p>Answer : Home</p>
    <hr />
    <p>General Maferath</p>
    <p>
      Riddle : A poison of the soul, passion’s cruel counterpart; from love she
      grows till love lies slain. Of what do I speak?
    </p>
    <p>Answer : Jealousy</p>
    <hr />
    <p>Archon Hessarian</p>
    <p>
      Riddle : She wields the broken sword, and separate true kings from
      tyrants. Of what do I speak?
    </p>
    <p>Answer : Mercy</p>
    <hr />
    <p>Disciple Cathaire</p>
    <p>
      Riddle : No man has seen it but all men know it. lighter than air, sharper
      than any sword. Comes from nothing, but will fell the strongest armies. Of
      what do I speak?
    </p>
    <p>Answer : Hunger</p>
    <hr />
    <p>Disciple Havard</p>
    <p>
      Riddle : The bones of the world stretch towards the sky’s embrace. Veiled
      in white, like a bride greeting her groom. Of what do I speak?
    </p>
    <p>Answer : The mountains</p>
    <hr />
    <p>Lady Vasilia</p>
    <p class="mb-5">
      Riddle : An eye for an eye, a tooth for a tooth. The debt of blood must be
      paid in full. Of what do I speak?
    </p>

    <h5>bridge puzzle</h5>
    <p class="fw-bold">step 1:</p>
    <img src={bridge1} alt="bridge" />
    <p class="fw-bold">step 2:</p>
    <img src={bridge2} alt="bridge" />
    <p class="fw-bold">step 3:</p>
    <img src={bridge3} alt="bridge" />
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<style>
  p.fw-bold {
    text-align: center;
    text-transform: capitalize;
  }

  img {
    display: block;
    margin: auto;
    margin-bottom: 30px;
  }

  @media screen and (max-width: 600px) {
    div {
      width: 100%;
    }
  }
</style>
