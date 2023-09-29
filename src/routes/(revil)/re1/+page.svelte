<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "Resident Evil 1 Remake";
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
      <li><a href="#trophies">trophies</a></li>
      <li><a href="#wvane">weathervane</a></li>
      <li><a href="#vjolt">V-Jolt</a></li>
      <li><a href="#sharks">aqua ring</a></li>
      <li><a href="#lab">lab</a></li>
    </ul>
  </div>

  <div id="trophies">
    <h4>trophies</h4>
    <h5>100% completion</h5>
    <div class="d-flex">
      <ul>
        <li>Platinum Splattin' 'Em!</li>
        <p>earn all trophies</p>
        <li>Like Taking Candy from a Baby</li>
        <p>Finish the game on Very Easy difficulty or higher.</p>
        <li>Not in the Mood to Die</li>
        <p>Finish the game on Easy difficulty or higher.</p>
        <li>Take that, Zombies!</li>
        <p>Finish the game on Normal difficulty or higher.</p>
        <li>Oh, the Horror</li>
        <p>Finish the game on Hard difficulty.</p>
        <li>We're in This Together</li>
        <p>Finish the game with Jill and Chris.</p>
        <li>the survival horror</li>
        <p>Finish the game in Real Survival mode.</p>
        <li>ghost of a chance</li>
        <p>Finish the game in Invisible Enemy mode.</p>
        <li>not just any object</li>
        <p>Obtain the Stone & Metal Object using Chris.</p>
        <li>herbicide</li>
        <p>Defeat Plant 42 using Chris.</p>
        <li>written word is dead</li>
        <p>Obtain the "Last Book Vol. 2" using Chris.</p>
        <li>An End to a Poor Girl's Misery</li>
        <p>Defeat Lisa Trevor using Chris.</p>
        <li>You da Man, Chris</li>
        <p>Finish the game using Chris.</p>
        <li>grave digger</li>
        <p>Defeat a Crimson Head prototype1 using Jill.</p>
        <li>the key master</li>
        <p>Obtain the Helmet Key using Jill.</p>
        <li>Giant Snake Got Nothin'</li>
        <p>Defeat Yawn using Jill.</p>
        <li>where the magic happens</li>
        <p>Break into the laboratory using Jill.</p>
        <li>alpha team's finest</li>
        <p>Finish the game using Jill.</p>
        <li>get used to it</li>
        <p>Die for the first time.</p>
        <li>first kills are special</li>
        <p>Defeat a zombie.</p>
        <li>not taking any chances</li>
        <p>Burn up a zombie.</p>
        <li>Who's the Hunter Now?</li>
        <p>defeat a hunter</p>
        <li>bravo, rebecca</li>
        <p>Save Chris using Rebecca.</p>
      </ul>
      <ul>
        <li>what a great guy</li>
        <p>Save Jill using Barry.</p>
        <li>Delaying the Inevitable</li>
        <p>Save Richard with a serum.</p>
        <li>that was nice of you</li>
        <p>Save Rebecca from a Hunter.</p>
        <li>trust him</li>
        <p>Save Barry from Lisa Trevor.</p>
        <li>sorry i made you wait</li>
        <p>Save Jill from confinement using Chris.</p>
        <li>sorry about the wait</li>
        <p>Save Chris from confinement using Jill.</p>
        <li>the nightmare ends</li>
        <p>Finish the game saving Rebecca and Jill using Chris.</p>
        <li>I'm a Member of S.T.A.R.S.</li>
        <p>Finish the game saving Chris and Barry using Jill.</p>
        <li>every man for himself</li>
        <p>Finish the game without saving anyone using Chris.</p>
        <li>every woman for herself</li>
        <p>Finish the game without saving anyone using Jill.</p>
        <li>seeing red</li>
        <p>Defeat a Crimson Head.</p>
        <li>not waiting to exhale</li>
        <p>Survive your first encounter with Yawn.</p>
        <li>deep sixed</li>
        <p>Defeat mother Neptune.</p>
        <li>spider sense</li>
        <p>Defeat Black Tiger.</p>
        <li>don't stop running</li>
        <p>Finish the game in three hours.</p>
        <li>racing and pacing</li>
        <p>Finish the game in five hours.</p>
        <li>CQC FTW</li>
        <p>Finish the game using only your knife (no lighter, Defensive Items, and stomping zombie heads).</p>
        <li>ink is for squids</li>
        <p>Finish the game without saving.</p>
        <li>Break Out the Marshmallows!</li>
        <p>Burn up two zombies at the same time with the lighter.</p>
        <li>starsenal</li>
        <p>Obtain all weapons (must load grenade launcher with all shell types).</p>
        <li>passion for fashion</li>
        <p>Obtain all costumes.</p>
        <li>Every Nook and Cranny</li>
        <p>Visit all places on all maps.</p>
      </ul>
    </div>
  </div>

  <div class="weathervane text-center" id="wvane">
    <h4>weathervane puzzle</h4>

    <p>red = west</p>
    <p>blue = north</p>
  </div>

  <div class="v-jolt" id="vjolt">
    <h4>Making V-Jolt</h4>

    <div class="mx-auto">
      <ol>
        <li>Water + chem 3 = chem 4</li>
        <li>chem 4 + chem 6 = chem 10</li>
        <li>Water + chem 6 = chem 7</li>
        <li>chem 7 + chem 10 = chem 17</li>
        <li>chem 17 + chem 3 = V-Jolt</li>
      </ol>
    </div>
  </div>

  <div class="sharks" id="sharks">
    <h4>Aqua Ring</h4>

    <div class="mx-auto">
      <ol>
        <li>Check center console</li>
        <li>Check right console</li>
        <li>Check left console</li>
        <li>Check pressure console</li>
        <li>Check right console</li>
        <li>Check left console</li>
        <li>Check center console</li>
      </ol>
    </div>
  </div>

  <div class="login text-center" id="lab">
    <h4>Lab Username and Password</h4>

    <p>Username: JOHN</p>
    <p>Password: ADA</p>
    <p>B2F - pass: CELL</p>
    <p>B3F</p>
  </div>

  <div class="panel text-center">
    <h4>Lab Number Panel</h4>
    <p>Code: 8462</p>
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<style>

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
