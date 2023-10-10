<script>
  import { pageTitle } from "$lib/stores.js";
  pageTitle.set("Resident Evil 4 Remake");
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
      <li><a href="#rank">rank</a></li>
      <li><a href="#bonus">Unlockables</a></li>
      <li><a href="#dolls">Clockwork Castellan</a></li>
    </ul>
  </div>

  <div id="rank">
    <h4>rank guide</h4>
    <h5>assisted</h5>
    <table
      class="table table-borderless table-dark table-striped table-responsive"
    >
      <thead>
        <tr>
          <th>rank</th>
          <th>S+</th>
          <th>S</th>
          <th>A</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th>time</th>
          <td>4 hours</td>
          <td>4 hours</td>
          <td>15 hours</td>
        </tr>
        <tr>
          <th>playthrough</th>
          <td>1</td>
          <td>any</td>
          <td>any</td>
        </tr>

        <tr>
          <th>saves</th>
          <td>unlimited</td>
          <td>unlimited</td>
          <td>unlimited</td>
        </tr>
      </tbody>
    </table>
    <h5>standard</h5>
    <table
      class="table table-borderless table-dark table-striped table-responsive"
    >
      <thead>
        <tr>
          <th>rank</th>
          <th>S+</th>
          <th>S</th>
          <th>A</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th>time</th>
          <td>5 hours</td>
          <td>5 hours</td>
          <td>12 hours</td>
        </tr>
        <tr>
          <th>playthrough</th>
          <td>1</td>
          <td>any</td>
          <td>any</td>
        </tr>

        <tr>
          <th>saves</th>
          <td>unlimited</td>
          <td>unlimited</td>
          <td>unlimited</td>
        </tr>
      </tbody>
    </table>
    <h5>hardcore</h5>
    <table
      class="table table-borderless table-dark table-striped table-responsive"
    >
      <thead>
        <tr>
          <th>rank</th>
          <th>S+</th>
          <th>S</th>
          <th>A</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th>time</th>
          <td>5 hours 30 min.</td>
          <td>5 hours 30 min.</td>
          <td>10 hours</td>
        </tr>
        <tr>
          <th>playthrough</th>
          <td>1</td>
          <td>any</td>
          <td>any</td>
        </tr>
        <tr>
          <th>saves</th>
          <td>unlimited</td>
          <td>unlimited</td>
          <td>unlimited</td>
        </tr>
      </tbody>
    </table>
    <h5>professional</h5>
    <table
      class="table table-borderless table-dark table-striped table-responsive"
    >
      <thead>
        <tr>
          <th>rank</th>
          <th>S+</th>
          <th>S</th>
          <th>A</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th>time</th>
          <td>5 hours 30 min.</td>
          <td>5 hours 30 min.</td>
          <td>7 hours</td>
        </tr>
        <tr>
          <th>playthrough</th>
          <td>1</td>
          <td>any</td>
          <td>any</td>
        </tr>

        <tr>
          <th>saves</th>
          <td>15</td>
          <td>unlimited</td>
          <td>unlimited</td>
        </tr>
      </tbody>
    </table>
  </div>

  <div id="bonus">
    <h4>unlockables</h4>
    <div class="d-flex">
      <div>
        <h5>primal knife</h5>
        <p>1,000 CP</p>
        <p class="fw-bold">How to unlock:</p>
        <p>Destroy all 16 clockwork castellans</p>
      </div>
      <div>
        <h5>handcannon</h5>
        <p>1,000 CP</p>
        <p class="fw-bold">How to unlock:</p>
        <p>Beat professional with no bonus weapons.</p>
        <p>Mercenaries: S rank on all stages with a single character.</p>
      </div>
      <div>
        <h5>chicago sweeper</h5>
        <p>1,000 CP</p>
        <p class="fw-bold">How to unlock:</p>
        <p>Beat Professional with an A rank.</p>
      </div>
    </div>
    <div class="d-flex">
      <div>
        <h5>ashley armor</h5>
        <p>2,000 CP</p>
        <p class="fw-bold">How to unlock:</p>
        <p>Beat Hardcore with an A rank.</p>
      </div>
      <div>
        <h5>cat ears</h5>
        <p>2,000 CP</p>
        <p class="fw-bold">How to unlock:</p>
        <p>Beat Professional with S+ rank.</p>
      </div>
    </div>
  </div>

  <div id="dolls">
    <h4>clockwork castellan</h4>
    <ol>
      <li>
        <p class="fw-bold">Chapter 1:</p>
        <p>First house at lakeside settlement. Before finding Luis.</p>
      </li>
      <li>
        <p class="fw-bold">Chapter 2:</p>
        <p>Small shack just before village chief's manor.</p>
      </li>
      <li>
        <p class="fw-bold">Chapter 3:</p>
        <p>Down the ladder below the merchant.</p>
      </li>
      <li>
        <p class="fw-bold">Chapter 4:</p>
        <p>
          Sail back to lakeside settlement and open the locked gate. Climb the
          ladder in the newly unlocked area to reach the Forest Altar.
        </p>
      </li>
      <li>
        <p class="fw-bold">Chapter 5:</p>
        <p>In the attic of the village chief's manor.</p>
      </li>
      <li>
        <p class="fw-bold">Chapter 6:</p>
        <p>Sitting at the base of the large bonfire.</p>
      </li>
      <li>
        <p class="fw-bold">Chapter 7:</p>
        <p>
          After defeating the Garrador in the castle's dungeon, use the Dungeon
          Key to unlock the door by Ashley and climb up the ladder that follows.
          You'll find yourself in a storage area that leads to the Treasury.The
          seventh Clockwork Castellan will be atop the shelves found toward the
          center of the room.
        </p>
      </li>
      <li>
        <p class="fw-bold">Chapter 8:</p>
        <p>
          The eighth Clockwork Castellan is located at the top of one of the
          towers in the Castle Battlements that you'll need to traverse while
          the massive, ogre-like enemy throws boulders at you. Immediately after
          the brief cutscene that reveals the monster, head to the right side of
          the tower and drop down. Continue to the right and climb up the ladder
          across the way while being careful to avoid incoming boulders.
        </p>

        <p>
          Once you reach the top of the ladder, you'll notice some crates to
          your right. To find this Wind-Up Doll you'll want to wrap around the
          area to reach the other side of these crates. The Clockwork Castellan
          will be waiting for you on some stacked sandbags.
        </p>
      </li>
      <li>
        <p class="fw-bold">Chapter 9:</p>
        <p>
          At the beginning of Chapter 9, you'll find yourself in a room with a
          Typewriter and the ninth Clockwork Castellan is located underneath the
          staircase that you'll walk down to enter the Courtyard. To reach the
          collectible, make your way through the maze while heading toward the
          northwestern reaches of the area. For more precise directions, refer
          to the list below that begins when standing directly in front of and
          facing the staircase toward the center of the area:
        </p>

        <ul>
          <li>Go down path to the left</li>
          <li>take a right at the end of the path</li>
          <li>take a left</li>
          <li>wrap around the right side of the hedge in front of you</li>
          <li>
            Take a final right and find the Clockwork Castellan hiding behind
            junk and near a First Aid Spray
          </li>
        </ul>
      </li>
      <li>
        <p class="fw-bold">Chapter 10:</p>
        <p>
          Across from the purple-flamed torch, you'll notice a metal grate.
          Approach the grate and you'll spot the tenth Clockwork Castellan
          hanging upside down behind the metal bars.
        </p>
      </li>
      <li>
        <p class="fw-bold">Chapter 11:</p>
        <p>
          The eleventh Clockwork Castellan can be found in the Stopover area
          that you'll enter after your rollercoaster-like minecart experience.
          Defeat the enemies guarding the ruined structure and look above the
          central door to find this Wind-Up Doll.
        </p>
      </li>
      <li>
        <p class="fw-bold">Chapter 12:</p>
        <p>
          The twelfth Clockwork Castellan is found on the ground floor of the
          Clock Tower. After entering the Clock Tower, defeat any enemies in
          your way while heading toward the northwestern end of the area. The
          Clockwork Castellan will be on some boxes under the staircase.
        </p>
      </li>
      <li>
        <p class="fw-bold">Chapter 13:</p>
        <p>
          Just to the right of the Elegant Crown Treasure, you'll notice heavy
          machinery including a green forklift. The thirteenth Clockwork
          Castellan will be on the floor and between the heavy machinery.
        </p>
      </li>
      <li>
        <p class="fw-bold">Chapter 14:</p>
        <p>
          Immediately after the cutscene in which Saddler kidnaps Ashley, push
          through the doors to chase after them, then head down the path on your
          right to reach an area overlooking the Campsite. Take out the enemy
          here, then enter the small control room to your right. The fourteenth
          Clockwork Castellan will be sitting on top of the lockers in this
          control room.
        </p>
      </li>
      <li>
        <p class="fw-bold">Chapter 15:</p>
        <p>
          The fifteenth Clockwork Castellan can be found after the cutscene in
          which the helicopter pilot, Mike, meets his untimely demise. After the
          cutscene, make your way toward the objective and head into the nearby
          building. Defeat the Regenerador inside and enter the small room to
          the right of the wheel mechanism.
        </p>

        <p>
          This room has a vertical beam at the center of it. Look upward from
          the beam and this Clockwork Castellan will be sitting on the
          perpendicular beam.
        </p>
      </li>
      <li>
        <p class="fw-bold">Chapter 16:</p>
        <p>
          The final Clockwork Castellan can be found during the countdown
          sequence that begins after you've vanquished Saddler. Sprint through
          the opening area of the Underground Passage and jump across the
          falling bridge with Ashley. As you approach the door, an enemy will
          leap onto you before falling to the ground.
        </p>

        <p>
          The Clockwork Castellan will be in this room. To find it, look toward
          the right-hand side and the Wind-Up Doll will be atop some crates near
          a forklift.
        </p>
      </li>
    </ol>
  </div>

  <a href="#top" class="skiplink">Top</a>
</div>

<style>
  table th {
    text-transform: capitalize;
  }

  @media screen and (max-width: 600px) {
    table tr {
      display: flex;
      flex-direction: column;
    }
  }
</style>
