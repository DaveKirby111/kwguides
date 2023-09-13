<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "Final Fantasy VII";
  import Sections from "$lib/sections.svelte";
  import harp1 from "$lib/images/ff7/harp1.png";
  import harp2 from "$lib/images/ff7/harp2.png";
  import key1 from "$lib/images/ff7/key1.png";
  import key2 from "$lib/images/ff7/key2.png";

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
      <p>Black Chocobo Save Editor</p>
      <p>
        <a
          href="http://www.blackchocobo.com/"
          target="_blank"
          rel="noopener noreferrer">Visit Site</a
        >
      </p>
    </div>
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<div id="guides" class="guides">
  <h2>guides</h2>

  <div class="guide-sections">
    <p class="fw-bold text-decoration-underline">Sections</p>
    <ul class="skip">
      <li><a href="#yuffie">yuffie</a></li>
      <li><a href="#vincent">vincent</a></li>
      <li><a href="#date">gold saucer date</a></li>
      <li><a href="#ultimate">ultimate weapons/limits</a></li>
      <li><a href="#harp">lunar harp</a></li>
    </ul>
  </div>

  <div class="yuffie mb-5" id="yuffie">
    <h5>how to get Yuffie</h5>
    <p>
      Yuffie is found in any of the game's forests. The forests near Junon seem
      to be the first opportunity to recruit her. She is encountered randomly
      like any monster encounter. After fighting and defeating her, the player
      must choose a series of correct dialogue options.
    </p>

    <ul>
      <li>Yuffie: "One more time, let's go one more time!"</li>
      <li>Answer: Not interested</li>
    </ul>

    <ul>
      <li>Yuffie: "You're pretty scared of me, huh!?"</li>
      <li>Answer: ...petrified</li>
    </ul>

    <ul>
      <li>Yuffie: "I'm really gonna leave! REALLY!"</li>
      <li>Answer: Wait a second</li>
    </ul>

    <ul>
      <li>Yuffie: "You want me to go with you?"</li>
      <li>Answer: ...That's right</li>
    </ul>

    <ul>
      <li>Yuffie: "All right! I'll go with you!"</li>
      <li>Answer: ...Let's hurry on</li>
    </ul>
  </div>

  <div class="vincent mb-5" id="vincent">
    <h5>how to get Vincent</h5>

    <p>
      Vincent can be found in the basement of Shinra Mansion in Nibelheim.
      Getting to him requires finding the combination to a safe that holds a key
      to the room he is in. Upon opening the safe there will be a boss fight.
    </p>

    <p class="fw-bold">Combination:</p>
    <p>
      Note: The combination must be entered in 20 seconds or less and you can
      not go past the number.
    </p>

    <ul>
      <li>Clue: The lid of the box with the most oxygen</li>
      <li>
        This clue can be found by examining the empty treasure chest on the
        second floor that contained the Enemy Launcher weapon for Barret.
      </li>
    </ul>

    <ul>
      <li>Clue: Behind the Ivory’s short of tea and ray.</li>
      <li>
        This clue refers to the ivory keys of the piano which can be found in
        the room through the doorway to the left of the staircase (on the main
        floor). Just short of tea and ray refers to it being close to the tea
        room and close to the sun rays coming through the stained class.
      </li>
    </ul>

    <ul>
      <li>Clue: The creek in the floor near the chair…</li>
      <li>
        This clue is located in the hallway of the second floor in the rooms to
        the right (use the screenshot to guide you).
      </li>
    </ul>

    <ul>
      <li>
        Dial 4: The fourth row has been written in invisible ink… Dial 4 = 97
      </li>
    </ul>

    <p class="fw-bold">Right = 36 -> Left = 10 -> Right = 59 -> Right = 97</p>

    <p>
      Step 1: Part way along the pathway to the library is a wooden doorway at
      the top of the screen. Proceed through the doorway which is now
      automatically open and examine the coffin at the back of the room.
    </p>

    <p>
      Step 2: Choose to “talk about Sephiroth” when presented with the option.
      Open the coffin again after Vincent shuts it and choose “Who are you?”
      from the options presented and you will get to name Vincent. As you
      attempt to leave the area Vincent will offer to join your party.
    </p>
  </div>

  <div class="date mb-5" id="date">
    <h5>Gold Saucer Date</h5>

    <p>
      Each character that Cloud can go out on a date with (Aeris, Tifa, Yuffie
      and Barret) start with a certain number of points. These points are
      hidden; you cannot tell how many points each character has. Each character
      starts off with the following number of points.
    </p>

    <ul class="list-group mb-3">
      <li class="list-group-item">Aeris: 50</li>
      <li class="list-group-item">Tifa: 30</li>
      <li class="list-group-item">Yuffie: 10</li>
      <li class="list-group-item">Barret: 0</li>
    </ul>

    <p>
      Because of this configuration, most players tend to end up going on a date
      with Aeris. She starts with the highest point values and a lot of the
      choices and dialogue is setup in such a way that typically result in her
      receiving a high number of points. The points can be adjusted based on
      actions you take or dialogue that you select. Each area where the point
      values are impacted are listed below:
    </p>

    <p class="fw-bold">Sector 8</p>

    <p>
      Buying a flower from Aeris does not impact her points so either option is
      fine.
    </p>

    <ul>
      <li>After Jessie explains how the security system works:</li>
      <li>Thanks anyway = no change</li>
      <li>Looking forward to it = -3 to Tifa</li>
    </ul>

    <p class="fw-bold">7th Heaven</p>

    <ul>
      <li>Give flower to Tifa = +5 to Tifa</li>
      <li>Give flower to Marlene = +5 to Barret</li>
    </ul>

    <ul>
      <li>Talk to Tifa behind bar:</li>
      <li>I don't feel like it = no change</li>
      <li>Give ne something hard = +5 to Tifa</li>
    </ul>

    <ul>
      <li>When Tifa accuses Cloud of leaving you childhood friend:</li>
      <li>How can you say that = +5 to Tifa</li>
      <li>...Sorry = no change</li>
    </ul>

    <ul>
      <li>Tifa asks Cloud how he slept:</li>
      <li>Next to you, who wouldn't = +5 to Tifa</li>
      <li>Barret's snoring kept me up... = +5 to Barret</li>
    </ul>

    <ul>
      <li>Train:</li>
      <li>
        You will recieve +5 to Tifa and Barret if you are able to make though
        the train while avoiding securit lockdowns.
      </li>
    </ul>

    <p class="fw-bold">No. 5 Reactor</p>

    <ul>
      <li>After fighting Airbuster:</li>
      <li>Be strong = +2 to Barret</li>
      <li>I don't know if I can hold on = +1 to Tifa, -3 to Barret</li>
    </ul>

    <p class="fw-bold">Sector 5 slums</p>

    <ul>
      <li>Push a wrong barrel = -3 to Aeris</li>
      <li>Ask Aeris to fight soldiers = -1 to Aeris</li>
      <li>Ask Aeris to run = no change</li>
      <li>Ask her to run and she ends up fighting = -1</li>
      <li>Push a correct barrel = +1</li>
    </ul>

    <p class="fw-bold">Aerith's House</p>

    <ul>
      <li>Ask will ask if Tifa is Cloud's girlfriend:</li>
      <li>Yeah, that's right = -5 to Aerith</li>
    </ul>

    <ul>
      <li>After you get to the playground:</li>
      <li>take her home = no change</li>
      <li>go on to sector 7 = +1 to Aerith</li>
    </ul>

    <p class="fw-bold">Wall Market</p>

    <ul>
      <li>If Tifa is chosen:</li>
      <li>you alright? = +3 to Aerith</li>
      <li>We gotta help Tifa = -2 to Aerith</li>
    </ul>

    <ul>
      <li>If Aerith is chosen:</li>
      <li>you alright? = +3 to Tifa</li>
      <li>We gotta help Aerith = -2 to Tifa</li>
    </ul>

    <ul>
      <li>If Cloud is chosen:</li>
      <li>yes, and his name's Barret = +5 to Barret</li>
    </ul>

    <p class="fw-bold">Sewer</p>

    <ul>
      <li>Talk to Aerith first = +3 to Aerith</li>
      <li>Talk to Tifa first = +3 to Tifa</li>
    </ul>

    <p class="fw-bold">Sector 6</p>

    <ul>
      <li>Marlene suggests that Aerith likes Cloud:</li>
      <li>I don't know = +3 to Tifa, -3 to Aerith</li>
      <li>Let's hope so = +3 to Aerith, -3 to Tifa</li>
    </ul>

    <p class="fw-bold">Shinra Building</p>

    <ul>
      <li>When you first meet Red XIII:</li>
      <li>Tifa, I'm counting on you = -2 to Tifa</li>
      <li>Barret, take care of her = +2 to Barret</li>
    </ul>

    <ul>
      <li>
        After battle against HO512, adding any of the following to your team:
      </li>
      <li>Aerith = +2</li>
      <li>Barret = +2</li>
      <li>Tifa = +2</li>
    </ul>

    <ul>
      <li>When Tifa asks if you can break out:</li>
      <li>Leave it to me = +1 to Tifa</li>
      <li>Kinda Hard = -1 to Tifa</li>
    </ul>

    <ul>
      <li>When you have the option to think of Barret, Red XIII, or Aerith:</li>
      <li>Barret or Aerith first = +3 to first selection</li>
      <li>Barret or Aerith second = +1 to second</li>
      <li>Barret of Aerith third = no change</li>
    </ul>

    <ul>
      <li>Adding members to your party as you escape and leave Midgar:</li>
      <li>+1 to whoever you add to party</li>
    </ul>

    <p class="fw-bold">Kalm</p>

    <ul>
      <li>When Barret leaved the inn:</li>
      <li>Wait a sec = no change</li>
      <li>Beautiful, just beautiful = +3 to Barret</li>
      <li>Is that all? = -1 to Barret</li>
      <li>Right = +1 to Barret</li>
    </ul>

    <ul>
      <li>
        There is a woman in the house to the right of the Kalm Inn. Speaking to
        the woman in Kalm who says that Mako energy is convenient, answer with:
        (if they are in your party)
      </li>
      <li>
        Yeah, maybe = -2 to Barret, -1 to Aerith, -1 to Tifa, +1 to Yuffie
      </li>
      <li>
        You're full of it = +2 to Barret, +1 to Aerith, +1 to Tifa, -1 to Yuffie
      </li>
    </ul>

    <ul>
      <li>
        There is a woman on the second floor of the same building. Speaking to
        the girl upstairs who thinks that the old life is better, answer with:
      </li>
      <li>
        Yeah, maybe = +2 to Barret, +1 to Aerith, +1 to Tifa, -1 to Yuffie
      </li>
      <li>No way = -2 to Barret, -1 to Aerith, -1 to Tifa, +1 to Yuffie</li>
    </ul>

    <ul>
      <li>Recruiting Yuffie:</li>
      <li>Not interested = +2 to Yuffie</li>
      <li>Petrified = +2 to Yuffie</li>
      <li>Wait a second = +2 to Yuffie</li>
      <li>That's Right = +2 to Yuffie</li>
      <li>Let's hurry = +2 to Yuffie</li>
    </ul>

    <p class="fw-bold">Fort Condor</p>

    <ul>
      <li>When you talk to old guy in Fort Condor: (if they are in party)</li>
      <li>I guess so = +5 to Barret, +3 to Aerith, +3 to Tifa, +2 to Yuffie</li>
      <li>
        Not interested = -5 to Barret, -3 to Aerith, -3 to Tifa, -1 to Yuffie
      </li>
    </ul>

    <ul>
      <li>After the old guy tells you about his problems:</li>
      <li>All right = +5 to Barret, +3 to Aerith, +3 to Tifa, +2 to Yuffie</li>
      <li>
        Not interested = -5 to Barret, -3 to Aerith, -3 to Tifa, -1 to Yuffie
      </li>
    </ul>

    <p class="fw-bold">Cargo Ship</p>

    <ul>
      <li>Yuffie asks if you have anything for her stomach:</li>
      <li>Here, use this = +4 to Yuffie</li>
      <li>Nope = -2 to Yuffie</li>
      <li>
        Note: Automatic -2 if you do not have any Tranquilizers in your
        inventory.
      </li>
    </ul>

    <ul>
      <li>When Aerith asks about the airship:</li>
      <li>I'll take you someday = +2 to Aerith</li>
      <li>I dunno... = -2 to Aerith</li>
    </ul>

    <ul>
      <li>When Tifa asks about war:</li>
      <li>Yeah... = +2</li>
      <li>I don't know = -2</li>
    </ul>

    <p class="fw-bold">Gold Saucer</p>

    <p>
      When you have the option to have party members accompany Cloud. +3 to
      whoever you take, -2 to those you don't.
    </p>

    <p class="fw-bold">Corel Prison</p>

    <ul>
      <li>When you choose who to go with Cloud and Barret:</li>
      <li>Aerith = +10</li>
      <li>Tifa = +3</li>
      <li>Yuffie = +2</li>
    </ul>

    <p class="fw-bold">Gongaga</p>

    <p>After speaking to Zack's parents you can:</p>

    <ul>
      <li>Ignore and don't speak to Aerith = -3 to Aerith</li>
      <li>Speaking to Aerith -> poor guy = +1 to Aerith</li>
      <li>Speaking to Aerith -> ...jealous...envious... = +2 to Aerith</li>
      <li>Ignore Tifa = -3 to Tifa</li>
      <li>Speaking to Tifa -> all answers = +1 to Tifa</li>
    </ul>

    <p class="fw-bold">Cosmo Canyon</p>

    <ul>
      <li>Make sure Barret is in party. Talk to Barret in weapon shop:</li>
      <li>Go on = +3 to Barret</li>
      <li>not really = no change</li>
      <li>And then? = +3 to Barret</li>
      <li>Yeah, whatever = no change</li>
    </ul>

    <p class="fw-bold">Wutai</p>

    <ul>
      <li>
        If you go through the Wutai side quest with Yuffie = +10 to Yuffie
      </li>
    </ul>
  </div>

  <div class="ult-weapons" id="ultimate">
    <h5>Ultimate Weapons and Limit Breaks</h5>

    <p class="fw-bold">Cloud = Ultimate Weapon</p>
    <p>
      Can be obtained by defeating Ultimate Weapon (boss). Ultimate Weapon (the
      boss) is first fought in Mideel when you go to find and rescue Cloud after
      the battle at the Northern Crater / Whirlwind Maze. It reappears again
      after you have defeated Diamond Weapon just before parachuting into
      Midgar, though it is much easier to defeat Ultimate Weapon after you reach
      the end of the game on Disc 3.
    </p>

    <p>
      Omnislash = Use the Omnislash item to teach this Limit Break to Cloud. You
      can find the Omnislash item by completing the Battle Square side quest.
    </p>

    <p class="fw-bold">Barret = Missing Score</p>
    <p>
      It can be found when the team returns to Midgar to fight Dr. Hojo. The
      chest containing Missing Score can only be seen and obtained if Barret is
      in your party. Unfortunately, there is no way to return to this area of
      Midgar if you missed picking it up on your way through which means that
      there is no means to obtain Missing Score if you are already past this
      point in the game.
    </p>

    <p>
      Catastrophe = Use the Catastrophe item on Barret after he has learned all
      of his other Limit Breaks. Catastrophe can be obtained by revisiting
      Barret’s home town of North Corel after retrieving the Huge Materia and
      stopping the oncoming train.
    </p>

    <p class="fw-bold">Tifa = Premium Heart</p>
    <p>
      Premium Heart can be found by revisiting Midgar using the Key to Sector 5.
    </p>

    <p>
      You can complete the Key to Sector 5 side quest and reenter the Midgar
      slums anytime after Cloud rejoins your party after you’ve rescued Cloud
      from Mideel and gone through the Lifestream scenes. The quest involves
      digging up a key in Bone Village and traveling around the slums to pick up
      some items.
    </p>

    <p>
      Travel to Bone Village up on the northern continent. Speak to the man and
      ask to “Start diggin’” for “Good treasure”. The Key to Sector 5 can be
      found near the smashed up plane on the main level of the dig site.
    </p>

    <img src={key1} alt="key" />
    <img src={key2} alt="key" />

    <p>
      Final Heaven = Use the Final Heaven item on Tifa after she has learned all
      of her other Limit Breaks. Final Heaven can be obtained by revisiting
      Tifa’s home town of Nibelheim and completing a small side quest.
    </p>

    <p class="fw-bold">Aerith = Princess Guard</p>
    <p>
      It can be found in the clock room of the Temple of the Ancients. You do
      not get much of an opportunity to use it with her though so don’t worry
      about it if you missed this item.
    </p>

    <p>
      Great Gospel = Use the Great Gospel item on Aeris after she has learned
      all of her other Limit Breaks. Obtaining the Great Gospel item involves
      following a fairly complicated set of steps before you reach the Temple of
      the Ancients.
    </p>

    <p>
      Before you head to the Temple of the Ancients, travel back to the town of
      Nibelheim where you left the Buggy that you obtained when you escaped
      Corel Prison. Ride the Buggy back to Costa del Sol and drive it directly
      in to the town. Head down to where the ship is docked and pay the sailor
      100 gil to return back to Junon.
    </p>

    <p>
      You need to have Aeris learn her last Limit Break before you enter the
      Temple of the Ancients. If you have entered or completed the Temple of the
      Ancients you can no longer have her learn her last Limit Break and you
      will need to restart the game in order to obtain this trophy.
    </p>

    <p>
      Leave Junon and you will find the Buggy waiting just outside of Junon.
      Take the Buggy to the east and use it to cross a river. Search for a small
      cave on the side of the mountains shown in the screenshot below.
    </p>

    <p>
      Speak to the sleeping man in the cave and he will tell you some random
      statistic about your gameplay. He will tell you a different random
      statistic each time you enter and speak to him. You need to have him tell
      you how many battles you have participated in and you need to speak to him
      when the last two digits of the number of battle are odd numbers and are
      the same numbers.
    </p>

    <p>
      For example, this would be numbers like 199, 233, 355, 177, 99, etc. but
      it would not include numbers like 200, 222, 188 (because these numbers are
      even).
    </p>

    <p>
      Exit the cave and engage in battles until you reach the right number and
      then speak to the sleeping man again. He will wake up and give you a
      “Mythril” key item. If he gives you a Bolt Ring it is because the last two
      digits were even and not odd – keep engaging in battles if this is the
      case.
    </p>

    <p>
      Now take the Mythril key item, hop back in to the Buggy and go all the way
      back to the Gold Saucer Area. To the southeast of Gold Saucer is the small
      house out on the peninsula with the man who normally talks about the
      Keystone and where to find it. Offer to give him the Mythril and he will
      offer you the option of opening one of two chests – a small one and a
      large one. Great Gospel is contained in the small chest (located on the
      left side of the second floor).
    </p>

    <p class="fw-bold">Red XIII = Limited Moon</p>
    <p>
      All you have to do to obtain Red XIII’s Ultimate Weapon is revisit Cosmo
      Canyon on Disc 3.
    </p>

    <p>
      Cosmo Memory = Use the Cosmo Memory item to teach this Limit Break to Red
      XIII. You can find the Cosmo Memory item in the safe of the Shinra Mansion
      when you obtain Vincent as a playable character.
    </p>

    <p class="fw-bold">Yuffie = Conformer</p>
    <p>
      You can obtain Yuffie’s Ultimate Weapon, Conformer, by making a visit to
      the Sunken Gelnika which can be accessed after you have completed the
      Underwater Reactor section of the game and obtained the Shinra Sub as an
      accessible vehicle.
    </p>

    <p>
      All Creation = Use the All Creation item to teach this Limit Break to
      Yuffie. You can find the All Creation item by completing the Wutai Pagoda.
    </p>

    <p class="fw-bold">Vincent = Death Penalty</p>
    <p>
      obtained in Lucrecia’s Crystal Cave which can be reached anytime after you
      have obtained the Shinra Sub as a mobile vehicle. You can also get his
      level 4 limit break here.
    </p>

    <p class="fw-bold">Cid = Venus Gospel</p>
    <p>
      All you have to do is talk to the old man found in Rocket Town when you
      return to Rocket Town later on in the game. This can be done anytime after
      you have gone up into space and returned with (or without) the Huge
      Materia.
    </p>

    <p>
      Highwind = Use the Highwind item to teach this Limit Break to Cid. You can
      find the Highwind item in the Sunken Gelnika.
    </p>

    <p class="fw-bold">Caith Sith = HP Shout</p>
    <p>
      It can be retrieved during the second visit to Midgar in the Shinra
      Building towards the end of Disc 2. HP Shout, just like Missing Score,
      cannot be obtained if you miss them during your second visit to this area.
      There is no way to obtain them without restarting the game.
    </p>

    <p>Slots = Defeat 40 enemies in battle.</p>
  </div>

  <div class="harp" id="harp">
    <h5>Lunar Harp</h5>

    <p>
      Select the Lunar Harp for starters. You then have the option of placing
      the ‘staff’ in and around the dig site around the village. You can place
      as many as you like for 100 gil each and then once you detonate the
      explosive charge they will all point in the direction of the Lunar Harp.
      You can then select your dig point using the staff member’s line of site
      to help you triangulate the location.
    </p>

    <p>
      The Lunar Harp is located in the same place for everyone in every single
      playthrough. The location is just to the left of the rising smoke on the
      upper level of the village.
    </p>

    <div class="d-flex">
      <img src={harp1} alt="harp" />
      <img src={harp2} alt="harp" />
    </div>
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<style>
  img {
    width: 100%;
    height: auto;
  }

  .harp img {
    display: block;
    margin: auto;
    margin-bottom: 30px;
  }

  .list-group {
    width: 25%;
  }

  .div div {
    background-color: white;
    margin: 5px;
    border-radius: 15px;
    height: 200px;
    width: 20%;
    border-top: 55px solid black;
    border-bottom: 15px double black;
  }

  @media screen and (max-width: 600px) {
    .div div {
      width: 100%;
    }

    .list-group {
      width: 100%;
    }
  }
</style>
