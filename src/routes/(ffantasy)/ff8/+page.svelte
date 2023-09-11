<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "final fantasy VIII";
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
      <p>Hyne Save Editor</p>
      <p>
        <a
          href="https://www.nexusmods.com/finalfantasy8/mods/5?tab=description"
          target="_blank">Nexus Page</a
        >
      </p>
    </div>
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<div id="guides" class="guides">
  <h2>guides</h2>

  <ul class="skip">
    <p class="fw-bold text-decoration-underline">Sections</p>
    <li><a href="#tests">SeeD Tests</a></li>
    <li><a href="#deep">deep sea research center</a></li>
    <li><a href="#esthar">esthar</a></li>
    <li><a href="#gf">guardian forces</a></li>
  </ul>

  <div class="seed mb-5" id="tests">
    <h4>SeeD Tests</h4>

    <div class="d-flex">
      <table class="table table-dark table-striped table-responsive">
        <thead>
          <tr>
            <th>Exam</th>
            <th>Answers</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>1</td>
            <td>YNYYY NNYNN</td>
          </tr>
          <tr>
            <td>2</td>
            <td>YNYYY NYYNN</td>
          </tr>
          <tr>
            <td>3</td>
            <td>NNYNY YYNYN</td>
          </tr>
          <tr>
            <td>4</td>
            <td>NYYYN NYYNN</td>
          </tr>
          <tr>
            <td>5</td>
            <td>NNNYY NNYYY</td>
          </tr>
          <tr>
            <td>6</td>
            <td>YNYYN NYYNY</td>
          </tr>
          <tr>
            <td>7</td>
            <td>YYYYY YNYYN</td>
          </tr>
          <tr>
            <td>8</td>
            <td>NYNNY YNNYN</td>
          </tr>
          <tr>
            <td>9</td>
            <td>NYNNN NNNYY</td>
          </tr>
          <tr>
            <td>10</td>
            <td>YNNNN NNNYN</td>
          </tr>
        </tbody>
      </table>
      <table class="table table-dark table-striped">
        <thead>
          <tr>
            <th>Exam</th>
            <th>Answers</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>11</td>
            <td>YYNYY NYNNY</td>
          </tr>
          <tr>
            <td>12</td>
            <td>NYNNY NYNYN</td>
          </tr>
          <tr>
            <td>13</td>
            <td>YNNNY NNNNN</td>
          </tr>
          <tr>
            <td>14</td>
            <td>YYYYN YYNYN</td>
          </tr>
          <tr>
            <td>15</td>
            <td>YYNNN NNYNY</td>
          </tr>
          <tr>
            <td>16</td>
            <td>YNNYN YNNYN</td>
          </tr>
          <tr>
            <td>17</td>
            <td>YNNNY NNYNN</td>
          </tr>
          <tr>
            <td>18</td>
            <td>YNNNY NNNNN</td>
          </tr>
          <tr>
            <td>19</td>
            <td>YNNYN NNNNY</td>
          </tr>
          <tr>
            <td>20</td>
            <td>YYNYN YYYNN</td>
          </tr>
        </tbody>
      </table>
      <table class="table table-dark table-striped table-responsive">
        <thead>
          <tr>
            <th>Exam</th>
            <th>Answers</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>21</td>
            <td>YYYYN NYYYN</td>
          </tr>
          <tr>
            <td>22</td>
            <td>NNNYN NNYYN</td>
          </tr>
          <tr>
            <td>23</td>
            <td>YNNNN YYYYY</td>
          </tr>
          <tr>
            <td>24</td>
            <td>YYNNY YNNNY</td>
          </tr>
          <tr>
            <td>25</td>
            <td>YNYYY NNYNN</td>
          </tr>
          <tr>
            <td>26</td>
            <td>YYNYN YNYNN</td>
          </tr>
          <tr>
            <td>27</td>
            <td>NYNNN NYNYN</td>
          </tr>
          <tr>
            <td>28</td>
            <td>YNNYY YNYNN</td>
          </tr>
          <tr>
            <td>29</td>
            <td>NNNYY NNNYN</td>
          </tr>
          <tr>
            <td>30</td>
            <td>NYNNN NYNNN</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>

  <div class="center mb-5" id="deep">
    <h4>Deep Sea Research Center</h4>

    <h5>Fixed Encounters with Tri-faces:</h5>

    <p>
      Exit and then re-enter the Deep Sea Research Center but make sure that you
      have Zell in your party. Make your way down the hole that appeared right
      where the core (and Bahamut) used to be. There should now be a save point
      just outside the hole which you should make use of right now.
    </p>

    <p>
      Open the first gate and move down to the second level. Examine the
      terminal on the second level and choose to use 1 Reserve Steam Pressure
      (RSP). Go down to level 3 and use 1 RSP again. Continue using 1 RSP for
      each of the levels until you get to the bottom.
    </p>

    <p>
      When you get to the bottom level Zell will offer to “take care of this
      machine”. Choose to allow him to (“Well… Zell’s pretty good with
      machinery”) – Zell will then punch this doorway open for you – this will
      save some RSP (in order to fight Ultima Weapon you will need at least 10
      RSP).
    </p>

    <p>
      Walk towards the save point and you will be immediately thrown into battle
      against a Tri-Face, even if you have Diablos’ “Enc-None" ability active.
      In fact, you should make sure that you do have the Enc-None ability active
      so that you can restrict your fights to the fixed Tri-Face fights. Each
      time you walk past a certain point in the map you will fight a Tri-Face
      (there are three distinct locations). Each time you leave the screen and
      come back you will reset the fixed encounter points and you can fight 3
      more Tri-Faces!
    </p>
  </div>

  <div class="esthar mb-5" id="esthar">
    <h4>Esthar</h4>

    <h5>Fixed Encounters with Elnoyles</h5>

    <p>
      Land the Ragnarok at the Esthar Airstation as shown in the screenshot to
      the right. Make your way to area 14 of Esthar as shown on the map below.
      You can do this by heading right from the Airstation, north to area 2,
      north again to area 1 and then south into area 14.
    </p>

    <p>
      Tip: Remove the Mug ability, as this will prevent Elnoyle from dropping
      and Energy Crystals at the end of the battle.
    </p>

    <p>
      Speak to the black character on the bottom bridge to find out that it is
      actually an Elnoyle in disguise and this will immediately throw you into
      battle. After you have defeated the Elnoyle you can leave this screen and
      come back to reset the encounter.
    </p>
  </div>

  <div class="gf" id="gf">
    <h4>Guardian Forces</h4>

    <h5>Doomtrain</h5>

    <ul>
      <li>Solomon Ring</li>
      <li>Malboro Tentacle = 6</li>
      <li>Steel Pipe = 6</li>
      <li>Remedy+ = 6</li>
    </ul>

    <p class="fw-bold">Malboro Tentacles</p>
    <p>
      Malboro Tentacles can be won from or Mugged from Malboros, or you can
      refine the Malboro Card into a Malboro Tentacle. Malboros can be found on
      the Island Closest to Hell, the Island Closest to Heaven or in the
      Grandidi Forest, which is just outside the Chocobo Sanctuary. The Island
      Closest to Hell/Heaven are not reachable until you have Ragnarok, so you
      choices may be limited to the Grandidi Forest.
    </p>

    <p class="fw-bold">Steel Piple</p>
    <p>
      Make your way back to the Galbadia Garden area and find the nearby forest.
      You can Mug Steel Pipes from Wendigos.
    </p>

    <p class="fw-bold">Remedy+</p>
    <p>
      You can turn a regular Remedy into a Remedy+ using Alexander’s Med LV Up
      Ability.
    </p>
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<style>
  @media screen and (max-width: 600px) {
    table {
      display: flex;
      flex-direction: column;
    }

    table th,
    table td {
      width: 100%;
    }
  }
</style>
