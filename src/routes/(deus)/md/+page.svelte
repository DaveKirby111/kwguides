<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "deus ex: mankind divided";
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

  <div class="praxis">
    <h4>Praxis Kiets</h4>

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

  <div class="passwords mb-5">
    <h4>Passwords</h4>

    <div class="pw-1 d-flex">
      <div>
        <p class="fw-bold text-capitalize">zelen apartments</p>
        <ul>
          <li>apt. 41 = thevoidwhichbinds</li>
          <li>apt. 32 = Ouroboros</li>
          <li>apt. 31 = starlight</li>
          <li>apt. 23 = krodine</li>
          <li>apt. 22 = DobraNoc</li>
        </ul>
      </div>
      <div>
        <p class="fw-bold text-capitalize">other</p>
        <ul>
          <li>Time Machine front desk = Ubik</li>
          <li>Time Machine back room = heartofdarkness</li>
          <li>Toys factory = 1980</li>
          <li>Helena Volin's computer = KEPLER432B</li>
          <li>Felice Ullman's computer = LEPTONS</li>
          <li>Capek Fountain Station = Messier43</li>
          <li>Pawn Shop = VCORPP03L</li>
          <li>Neon Lab = ImCarcosa</li>
        </ul>
      </div>
      <div>
        <p class="fw-bold text-capitalize">church of the MachineGod</p>
        <ul>
          <li>security hubs = ascension</li>
          <li>Katjusa Vent = ElectricSpirit</li>
          <li>Dagmar Pala = FaithInU</li>
          <li>Allison Stanek = absolution</li>
        </ul>
      </div>
      <div>
        <p class="fw-bold text-capitalize">33 hlavni apartments</p>
        <ul>
          <li>apt. 202 = devotchka</li>
          <li>apt. 203 = Messier43</li>
          <li>apt. 203 = E4E5QH5</li>
          <li>apt. 302 = 1977</li>
        </ul>
      </div>
    </div>
    <div class="pw-2 d-flex">
      <div>
        <p class="fw-bold text-capitalize">stores</p>
        <ul>
          <li>Hemingway Fine Spirits = FURVENT6</li>
          <li>Sobchak Security = NOFATE</li>
          <li>Tubehouse Electronics = MASKEDCYBORG</li>
        </ul>
      </div>
      <div>
        <p class="fw-bold text-capitalize">apartments</p>
        <ul>
          <li>Stana Tomasek = May2020</li>
          <li>Oleg Drago = OCTAVARIUM</li>
          <li>Marta Babik = TheFinalCut</li>
          <li>Julien Bartek = MUSTBREAKU</li>
          <li>Milos Awadalla = NOMORE</li>
          <li>Enro Gozeyn = VENUS</li>
          <li>Madame Photograghe, Vadim Orlov = OL519xanadu</li>
          <li>Otar Botkoveli casino sec hub = otarminator</li>
          <li>Cassian Valente = ELEFSIS</li>
        </ul>
      </div>
      <div>
        <p class="fw-bold text-capitalize">misc</p>
        <ul>
          <li>Otar Botkoveli = NEBUKED</li>
          <li>Registration Office = samithedog</li>
          <li>Policie comp = Almeisan</li>
          <li>
            Sec terminal checkpoint (during martial law only) = AugBuster003
          </li>
          <li>Sec hub (martial law) = 1FreeWish</li>
        </ul>
      </div>
    </div>
    <div>
      <p class="fw-bold text-capitalize text-center">task force 29 HQ</p>
      <div class="d-flex">
        <div class="d-flex mx-auto">
          <ul>
            <li>Aria Argento = tuscany2023</li>
            <li>Peter Chang = Aphasia5689, Cha12f5g9e</li>
            <li>Duncan MacReady = Sharp007, McCr49f0eF</li>
            <li>Vincent Black = Origami1870, Bla14f5ku6</li>
            <li>Dr. Delara Auzenne = AUZ1LU51AT1</li>
            <li>Dr. Jennifer Phillips = Neuropozyne</li>
            <li>Dr. Daniel Fletcher = BertiLLon1870</li>
          </ul>
          <ul>
            <li>Jim Miller = E4E5QH5</li>
            <li>Server Admin = Clod04SFD8S</li>
            <li>NSN = JJKPOXZ774</li>
            <li>Security Holding Cells = NMKKHJ223</li>
            <li>Briefing Room = paulwestlind</li>
            <li>Aidan Green = withstrangeaeons</li>
            <li>Strickland Hall = ELVIRA88</li>
          </ul>
          <ul>
            <li>Ethan King = FrakkingUpTheA</li>
            <li>Benjamin Scott = dormata</li>
            <li>Meredith Yang = mcsteamy</li>
            <li>Robert Allen = T1000</li>
            <li>Alison Walchuck = ebert</li>
            <li>Ryan Baker = saveprivateroy</li>
          </ul>
        </div>
      </div>
    </div>
    <p class="fw-bold text-capitalize text-center">palisade property bank</p>
    <div class="d-flex">
      <div class="d-flex mx-auto">
        <ul>
          <li>Parking garage = copyreport00</li>
          <li>PPB garage security = PALSEC6579AT</li>
          <li>Ivana Drahos = highdata001</li>
          <li>Thomas Romanek = Egypt2030</li>
          <li>Security office, level 2 = KLMVP9951</li>
          <li>Level 1 sec office sec hub = AKLVD6681</li>
          <li>Level 1 sec office = P34T45WF</li>
          <li>Level 1 Exec safes A = hjtrv8865</li>
          <li>Level 1 Exec safes B = AKLVD6681</li>
          <li>Level 3 sec office sec hub = clemenza</li>
          <li>Level 3 IT services = linox2014</li>
        </ul>
        <ul>
          <li>Pavel Karmoni = nardinemorano</li>
          <li>Level 3 conference room = safeandsecure22</li>
          <li>Ashani Talwar = scheherezade</li>
          <li>Masaaki Oshiro = tycoon999</li>
          <li>Level 3 CEO/CTO = brtvz5524</li>
          <li>Picus Group corporate vault = n3wsm4ker</li>
          <li>Tarvos sec services = LKMN01259KNML</li>
          <li>Tai Yong Medical = GBNM45KLP53</li>
          <li>Corporate Vault (M12: The Heist) = VIPsec487Tv</li>
          <li>Corporate Vault (M12: The Heist) = PALSEC4654TI</li>
          <li>VersaLife = 5896KLM01BN</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="keycodes text-center">
    <h4>keycodes</h4>
  </div>
  <a href="#top" class="skiplink">Top</a>
</div>

<style>
  .pw-1 div {
    width: 25%;
  }

  .pw-2 div {
    width: 33.3%;
  }
</style>
