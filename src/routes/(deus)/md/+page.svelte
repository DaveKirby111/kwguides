<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "deus ex: mankind divided";
  import Sections from "$lib/sections.svelte";
  import keycodes from "$lib/docs/Keycodes.pdf";
  import passwords from "$lib/docs/Passwords.pdf";

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

  <ul class="skip">
    <p class="fw-bold text-decoration-underline">Sections</p>
    <li><a href="#praxis">praxis</a></li>
    <li><a href="#passkey">passwords/kecodes</a></li>
  </ul>

  <div class="praxis" id="praxis">
    <h4>Praxis Kits</h4>

    <h5>prague</h5>
    <ol>
      <li>
        4 kits (in total) are sold by Tars (merchant in Zelen Apartments, apt.
        21) for 10000 credits each.
      </li>
      <ul>
        <li>
          2 kits are available during the first visit to Prague (unobtainable
          after leaving for Golem City)
        </li>
        <li>
          1 kit is available after returning from Golem City (unobtainable after
          leaving for G.A.R.M.).
        </li>
        <li>1 kit is available after returning from G.A.R.M.</li>
      </ul>
      <li>
        In the Zelen Apartments, apt. 32 (the one with the eviction sign one
        floor below Jensen's), in a hidden floorboard right below the window.
      </li>
      <li>
        In Koller's dungeon, inside a safe in the gas-filled room accessible via
        a hidden vent near the elevator. Interact with a painting near the
        elevator door to access the hidden vent. The safe also contains the
        triangle code #14.
      </li>
      <li>
        In TF29 HQ Infirmary, inside a medical box on an upper shelf (on the
        wall that borders with the storeroom).
      </li>
      <li>In the ceiling of the LIMB clinic, inside one of the cardboxes.</li>
      <li>
        In the Libuše Apartments, apt. 96, inside a box on top of the kitchen
        cabinets.
      </li>
      <li>
        In the Palisade Property Bank, in the secret room in the CEO's office.
      </li>
      <li>
        In the Palisade Property Bank, in Executive Safes B, in a level 5 safe
        under the turret.
      </li>
    </ol>

    <h5>golem city</h5>
    <ol>
      <li>
        In a medical box on the far side of the police-cordonned storage area
        near Sokol’s apartment.
      </li>
      <li>
        Completing the gold penguin task (The Golden Rookery) opens a hidden
        compartment containing a Praxis Kit.
      </li>
      <li>
        In the Ridit Station (located in ARC territory), in a room with a door
        labeled "350401." The door is at the north eastern part of the map of
        the Ridit Station, level 1. The kit is inside a wall-mounted container
        whose front is covered by a blue tarp. It is the room you can enter
        after dropping down a long shaft from Level 7 toward the right of the
        map. (See image)
      </li>
      <li>In a level 5 safe in Talos Rucker's security room in his office.</li>
    </ol>

    <h5>prague (post golem city)</h5>

    <ol>
      <li>
        In the Palisade Property Bank, in the Tai Yong Medical corporate vault.
      </li>
      <li>
        In Radich Nikoladze's office in the Dvali Theater, inside a safe behind
        a hidden panel on the red wall.
      </li>
      <li>
        In Allison Stanek's room on the top floor of the Church of the
        MachineGod, in the attic storage area above the terminals, accessible
        during and after the mission Confronting the Bomb-Maker. The Church of
        the MachineGod is also made accessible by progression through the
        alternative mission, The Heist.
      </li>
      <li>
        Can be obtained during the Fade to Black side mission - given to you by
        Olivie if you convinced Vlasta to smuggle Olivie (make sure to talk to
        her before leaving). This side mission is available only during the
        second visit to Prague.
      </li>
    </ol>

    <h5>london</h5>

    <ol>
      <li>On Viktor Marchenko's body</li>
    </ol>
  </div>

  <div class="key-pass d-flex" id="passkey">
    <div class="passwords text-center">
      <h4>Passwords</h4>
      <a href={passwords} target="_blank" rel="noopener noreferrer">Open PDF</a>
    </div>

    <div class="keycodes text-center">
      <h4>keycodes</h4>
      <a href={keycodes} target="_blank" rel="noopener noreferrer">Open PDF</a>
    </div>
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<style>
  .key-pass div {
    width: 50%;
  }
</style>
