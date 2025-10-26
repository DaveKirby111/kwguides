<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "Dragon Age: Inquisition";
  import Sections from "$lib/sections.svelte";

  // const sections = [
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
      <li><a href="#romance">romance</a></li>
      <li><a href="#election">divine election</a></li>
    </ul>
  </div>

  <div class="romance mb-5" id="romance">
    <h4>Romance</h4>

    <div class="cassandra">
      <h5>Cassandra</h5>

      <p class="fw-bold">Personal Quest: Promise of Destruction:</p>

      <p>War Table: Locate missing Seekers = Requires Influence Level 6.</p>

      <p>
        The romance can be initiated after winning Cassandra's approval,
        flirting with her on multiple occasions and completing her personal
        quest, Promise of Destruction.
      </p>

      <p class="fw-bold">Trespasser:</p>

      <p class="fst-italic">If Cassandra became Divine:</p>

      <p>
        The dialogue at the end of the main game indicates that she does not
        believe she and the Inquisitor will be able to continue their
        relationship. However, further dialogue from the Trespasser DLC leaves
        the status of their relationship in a more ambiguous state, with
        multiple indications that Cassandra and the Inquisitor may have
        continued their relationship from a distance (and possibly in secret as
        well).
      </p>

      <p class="fst-italic">Romanced:</p>

      <p>
        Regardless of her status as the Divine, she will be tricked by Varric
        into believing that the Inquisitor intends to propose to her, leading to
        a comical misunderstanding wherein Cassandra gently lectures an
        oblivious Inquisitor as to the "serious" subject of marriage. Though
        realizing the ruse leaves Cassandra feeling angry and embarrassed, it
        also gives the Inquisitor the opportunity to broach the question of
        marriage more earnestly.
      </p>

      <p>
        If Cassandra has been elected as Divine and the Inquisitor tries to
        broach the subject of marriage, she will firmly state that the two of
        them can never be wed, though she will still punctuate the conversation
        by affirming her love and dedication to him.
      </p>

      <p class="fst-italic">If Cassandra did not become Divine:</p>

      <p>
        She will express openness to the idea of marriage, claiming that she
        "will act very surprised" on the day of the Inquisitor's "truly romantic
        proposal". Cassandra will then follow this with a heartfelt declaration
        of love, stating that she will never leave the Inquisitor's side and
        that "not even the Maker Himself" could keep her away from her romantic
        partner.
      </p>
    </div>
  </div>

  <div class="divine" id="election">
    <h4>Divine Election</h4>

    <p>
      There are three candidates: Leliana, Cassandra and Vivienne (if
      recruited). The election system works very similarly to the approval
      system, but is completely separate from it. The candidates earn or lose
      points based on your choices throughout the game, and unlike the approval
      points, these are not indicated in any way to the player. Whoever
      accumulates the most points wins the election. If two candidates have the
      same number of points, Vivienne has a priority over both Cassandra and
      Leliana, Leliana has a priority over Cassandra.
    </p>

    <h5>About Leliana</h5>

    <ul>
      <li>
        The option to actually activate/trigger Leliana as a true candidate
        doesn't happen until after her personal quest is complete. Her personal
        quest actually can take place very late in the game compared to her
        rivals. Take care when talking with Cassandra or Vivienne as you can
        ruin Leliana's chance very early in the game. When talking with Vivienne
        or Cassandra be sure to not select an option that supports them as
        Divine, try to avoid it or even outright say that you don't support
        them.
      </li>

      <li>
        There is no war table operation to support Leliana's candidacy, so leave
        the operations to support Vivienne or Cassandra open/uncompleted until
        the endgame.
      </li>

      <li>
        Your choices with Leliana in her personal quest and throughout the game
        will change her demeanor in the epilogue. There is a "compassionate"
        ending and a "ruthless" version. Make your conversation choices
        carefully and save often.
      </li>
    </ul>

    <h5>War Table: Suppot Operations</h5>

    <ul>
      <li>Cassandra = +10</li>
      <li>Vivienne = +10</li>
      <li>No support option for Leliana</li>
    </ul>

    <h5>Inquisitor Speech</h5>

    <ul>
      <li>I'll do it because it's right = Leliana +5</li>
      <li>I will lead them to vengeance = Leliana +1, Vivienne -5</li>
      <li>I'll be a servant of faith = Cassandra +5, Vivienne +1</li>
      <li>
        A (Dwarf, Elf, Qunari) will stand for us all = Leliana +1, Cassandra -1,
        Vivienne -1
      </li>
      <li>Fight for order, not faith = Cassandra +1, Vivienne -1</li>
      <li>Set an example as a mage = Leliana +1, Vivienne +5</li>
      <li>I'll do it for my own power = Leliana -5, Cassandra -1</li>
    </ul>

    <h5>Conversations</h5>

    <p class="fw-bold">Cassandra:</p>

    <p>Cassandra and Giselle cutscene</p>

    <ul>
      <li>You'd be perfect = Cassandra +5</li>
      <li>Maybe the chantry should end = Leliana +1, Cassandra -1</li>
    </ul>

    <p>Do you want to be Divine?</p>

    <ul>
      <li>You'd make a good Divine = Cassandra +5</li>
      <li>Forget the chantry = Cassandra -5</li>
      <li>Perhaps there's another way = Cassandra -1</li>
    </ul>

    <p class="fw-bold">Leliana:</p>

    <p>After Wicked Eyes</p>

    <ul>
      <li>Chantry preached hate = Leliana +1</li>
    </ul>

    <p>After What Pride Had Wrought</p>

    <ul>
      <li>Why does change matter = Leliana +1</li>
      <li>It's a noble goal = Leliana +1</li>
      <li>I'd support you = Leliana +1</li>
      <li>The world needs that chantry = Leliana +1</li>
    </ul>

    <p class="fw-bold">Vivienne:</p>

    <p>Warm approval</p>

    <ul>
      <li>You hold the Divine to that?" = Vivienne +5</li>
    </ul>

    <p>After In Hushed Whispers/Champions of the Just</p>

    <ul>
      <li>"We need mages in the Chantry." = Vivienne +5</li>
      <li>"We need the Circle back." = Vivienne +1</li>
    </ul>

    <p>After Wicked Eyes and Wicked Hearts</p>

    <ul>
      <li>"You'd make a good Divine." = Vivienne +1</li>
      <li>"I agree." = Cassandra +1</li>
      <li>"What about Leliana?" = Leliana +1</li>
      <li>
        "I'll make sure they do." = This option requires the Nobility perk.
        Vivienne +5
      </li>
    </ul>

    <p class="fw-bold">Josphine:</p>

    <ul>
      <li>
        (About grand clerics consolidating the Chantry's power instead of
        comforting the masses) "It's needed more than ever." ("The Chantry
        should be a place of hope, not another group scrambling for answers.")
        Leliana +1, Vivienne +1
      </li>
    </ul>

    <p class="fw-bold">Mother Giselle:</p>

    <p>After In Hushed Whispers/Champions of the Just</p>

    <ul>
      <li>Chantry did terrible = Leliana +1</li>
    </ul>

    <p>After What Pride Had Wrought</p>

    <ul>
      <li>I hope so = Leliana +1</li>
    </ul>

    <p class="fw-bold">Dorian:</p>

    <ul>
      <li>
        (About the Chantry being a relic after, 'Are you religious?' is asked.
        Can be found within 'Investigate' after taking, 'The Imperium has a
        Chantry?' line of questioning. Available immediately upon recruiting
        him.) "I agree with you." ("I share your opinion, actually.") Leliana
        +1, Vivienne -1
      </li>
    </ul>

    <h5>Choices</h5>

    <p class="fw-bold">In Hushed Wispers</p>

    <ul>
      <li>Ally with mages = Leliana +10, Cassandra -5, Vivienne -10</li>
      <li>Make mages prisoners = Leliana -10, Cassandra +1, Vivienne +10</li>
    </ul>

    <p class="fw-bold">Champions of the Just</p>

    <ul>
      <li>Make them partners = Leliana +1, Cassandra +10, vivienne +5</li>
      <li>Make them serve = Leliana +1, Cassandra +5, Vivienne -5</li>
    </ul>

    <p class="fw-bold">Wicked Eyes and Wicked Hearts</p>

    <p>Celene dead:</p>

    <ul>
      <li>Gaspard and Briala rule = Leliana +5, Cassandra -5, Vivienne -10</li>
      <li>Gaspard alone = Cassandra +10, Vivienne -1</li>
    </ul>

    <p>Celene alive:</p>

    <ul>
      <li>Truce between all three = Cassandra +1, Vivienne -5</li>
      <li>Gaspard executed = Vivienne +1</li>
      <li>Gaspard spared = Leliana -1, Vivienne +5</li>
    </ul>

    <p class="fw-bold">Here Lies the Abyss</p>

    <ul>
      <li>Help the Inquisition = Leliana +5, Cassandra -5, Vivienne -1</li>
      <li>Banish them = Leliana -5, Cassandra +5, Vivienne +1</li>
    </ul>
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<style>
  @media screen and (max-width: 600px) {
    div {
      width: 100%;
      padding: 5px;
    }
  }
</style>
