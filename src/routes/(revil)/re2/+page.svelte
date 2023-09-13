<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "Resident Evil 2 Remake";
  import Sections from "$lib/sections.svelte";

  import claire1 from "$lib/images/re2/claire1.webp";
  import claire2 from "$lib/images/re2/claire2.webp";
  import leon1 from "$lib/images/re2/leon1.webp";
  import leon2 from "$lib/images/re2/leon2.webp";
  import lion from "$lib/images/re2/lion.jpg";
  import maiden from "$lib/images/re2/maiden.jpg";
  import unicorn from "$lib/images/re2/unicorn.jpg";

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
      <li><a href="#statues">statues</a></li>
      <li><a href="#combinations">combinations</a></li>
      <li><a href="#panels">electric panels</a></li>
      <li><a href="#chess">chess door puzzle</a></li>
      <li><a href="#lab">lab</a></li>
      <li><a href="#racoons">mr. racoon locations</a></li>
    </ul>
  </div>

  <div class="statues text-center" id="statues">
    <h4>Statues</h4>

    <h5 class="text-center">Lion</h5>
    <ul class="list-unstyled">
      <li>Police Station 1F, Main Hall</li>
      <li>Lion, Twig, Eagle / Crown, Flame, Flying Bird (B Scenario)</li>
    </ul>
    <img src={lion} alt="statue" />
    <h5 class="text-center">Unicorn</h5>
    <ul class="list-unstyled">
      <li>Station 2F, Lounge</li>
      <li>Fish, Scorpion, Aquarius / Twins, Scale, Worm (B Scenario)</li>
    </ul>
    <img src={unicorn} alt="statue" />
    <h5 class="text-center">Maiden</h5>
    <ul class="list-unstyled">
      <li>Police Station 3F, West Storage Room</li>
      <li>Woman, Bow, Snake / Ram, Harp, Bird (B Scenario)</li>
    </ul>
    <img src={maiden} alt="statue" />
  </div>

  <div class="combinations" id="combinations">
    <h4>Combinations</h4>

    <h5>Safes</h5>

    <ul>
      <li>West Office = left 9, right 15, left 7</li>
      <li>Waiting Room = left 6, right 2, left 11</li>
      <li>Treatment Pool = left 2, right 12, left 8</li>
    </ul>

    <h5>Locks</h5>

    <ul>
      <li>Rookie's First Assignment</li>
      <ul>
        <li>Right: MRG</li>
        <li>Left: NED</li>
      </ul>
      <li>Shower Room = CAP</li>
      <li>Locker near spade key = DCM</li>
      <li>Control Room = SZF</li>
    </ul>
  </div>

  <div class="panels" id="panels">
    <h4>Electric Panels</h4>

    <h5 class="text-center">Leon</h5>

    <div class="d-flex mb-5 m-auto">
      <div class="flex-column">
        <p class="fw-bold text-center">1st run</p>
        <img src={leon1} alt="panel" />
      </div>
      <div class="flex-column">
        <p class="fw-bold text-center">2nd run</p>
        <img src={leon2} alt="panel" />
      </div>
    </div>

    <h5 class="text-center">Claire</h5>

    <div class="d-flex m-auto">
      <div class="flex-column">
        <p class="fw-bold text-center">1st run</p>
        <img src={claire1} alt="panel" />
      </div>
      <div class="flex-column">
        <p class="fw-bold text-center">2nd run</p>
        <img src={claire2} alt="panel" />
      </div>
    </div>
  </div>

  <div class="chess" id="chess">
    <h4>Chess Door Puzzle</h4>

    <div class="d-flex justify-content-center">
      <div>
        <p class="fw-bold">1st run</p>
        <ul>
          <li>Knight - King</li>
          <li>Rook - Queen</li>
          <li>Bishop - Pawn</li>
        </ul>
      </div>

      <div>
        <p class="fw-bold">2nd run</p>
        <ul>
          <li>King - Knight</li>
          <li>Bishop - Rook</li>
          <li>Queen - Pawn</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="labcode" id="lab">
    <h4>Lab Code</h4>

    <div class="d-flex justify-content-center">
      <div>
        <p class="fw-bold">1st run</p>
        <p>3123 <br /> 2067</p>
      </div>

      <div>
        <p class="fw-bold">2nd run</p>
        <p>2048 <br /> 5831</p>
      </div>
    </div>
  </div>

  <div class="synthesis">
    <h4>Drug Lab Synethesis</h4>

    <p class="fw-bold">1st run</p>
    <p>Red, Green, Blue, Red, Green, Blue, Red, Green</p>
    <p class="fw-bold">2nd run</p>
    <p>Blue, Red, Green, Red, Blue, Red, Blue, Green, Blue, Red, Green</p>
  </div>

  <div class="racoons" id="racoons">
    <h4>Mr. Racoon Locations</h4>

    <ol>
      <li>West Office</li>
      <p>
        You'll find this Mr Raccoon early on in the game, on top of some boxes
        near the 'Welcome Leon' sign. This is the room where you solve the desk
        lock puzzle based on the initials of Leon's new colleagues—you'll run
        through it a bunch of times.
      </p>
      <li>STARS Office</li>
      <p>
        While you're up here trying to figure out how to get the magnum or
        grenade launcher, search the south side of the room to find a Mr Raccoon
        on the desks.
      </p>
      <li>Break Room</li>
      <p>
        It's not hard to find this Mr Raccoon in one of the game's save areas,
        particularly if you're picking through it for items anyway. He's behind
        a bag near the bunkbed by the sink. This is the first save room you
        access in Claire's campaign.
      </p>
      <li>Firing Range</li>
      <p>
        Like all the rooms in the basement, the Firing Range is not a
        particularly nice or bright area to explore, but you will find a Mr
        Raccoon here. Look by the targets on the floor inside the range itself.
      </p>
      <li>Chief's Office</li>
      <p>
        This Mr Raccoon is on a table by the stairs. You'll probably just come
        across this one by exploring.
      </p>
      <li>Clock Tower</li>
      <p>In the hallway</p>
      <li>Cafeteria</li>
      <p>
        This perpetually dark room is the location of another Mr Raccoon,
        perched on a table and near a television.
      </p>
      <li>Nap Room</li>
      <p>
        This one's a little harder to find, because you'll need to bring the
        power back online first to open up the shutters. It's in the pod next to
        the one containing a dead body on the right as you enter. You'll need to
        get the signal modulator and backtrack to this area—but doing so yields
        a modulator for Leon's flamethrower, and a high voltage condenser for
        Claire's sparkshot, so you'll wanna do it anyway.
      </p>
      <li>Supplies Storage</li>
      <p>
        Up the stairs that connect the Bottom Waterway and the Supplies Storage
        Room, Mr Raccoon can be found in the corner, obscured by a workbench.
      </p>
      <li>Alligator boss fight (Leon only)</li>
      <p>Near alligator corpse</p>
      <li>Incinerator Room (Ada section)</li>
      <p>
        This is an easy one to miss, since you don't play as Ada for long. Mr
        Raccoon is next to a pillar and some traffic cones near the incinerator
        room's door.
      </p>
      <li>East Storage Room (Claire only)</li>
      <p>
        There's a smaller room inside this one that requires the Heart key to
        open—so you'll need to be playing as Claire to grab this one.
      </p>
      <li>Bus behind RPD (Claire only)</li>
      <p>
        When you're wandering through this bus in one of the exteriors in
        Claire's campaign, you'll want to get Mr Raccoon on the dashboard.
      </p>
      <li>Nursery in Orphanage (Claire only)</li>
      <p>
        You'll find Mr Raccoon in the Nursery area of the Orphanage exclusive to
        Claire's campaign. He's hidden in a storage unit, that looks straight
        out of Ikea.
      </p>
      <li>Police Station Entrance (2nd run only)</li>
      <p>
        After you've fought this beastie as Leon—which isn't too hard, since you
        basically just run away for most of it—you'll find this Mr Raccoon on
        the left on a ledge in the room where you end up.
      </p>
    </ol>
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<style>
  .panels img {
    width: 100%;
    height: auto;
  }

  @media screen and (max-width: 600px) {
    div {
      padding: 5px;
    }
  }
</style>
