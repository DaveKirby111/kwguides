<script>
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "elder scrolls V: skyrim";
  import Sections from "$lib/sections.svelte";

  const sections = [
    {
      name: "console",
      link: "#console",
    },

    {
      name: "bat",
      link: "#bat",
    },

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

<div id="console" class="console" />
<div id="bat" class="bat" />
<div id="mods" class="mods">
  <h2>mods</h2>

  <div class="d-flex mb-5 justify-content-center">
    <div class="d-flex flex-column me-5 text-center">
      <p>Skyrim Script Extender</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/30379?tab=description"
          target="_blank">Nexus Page</a
        >
      </p>
    </div>
    <div class="d-flex flex-column me-5 text-center">
      <p>SkyUI</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/12604?tab=description"
          target="_blank">Nexus Page</a
        >
      </p>
    </div>
    <div class="d-flex flex-column me-5 text-center">
      <p>Unofficial Skyrim Special Edition Patch</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/266?tab=files&file_id=392477"
          target="_blank">Nexus Page</a
        >
      </p>
    </div>
    <div class="d-flex flex-column me-5 text-center">
      <p>Unofficial Skyrim Creation Club Patches</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/18975?tab=description"
          target="_blank">Nexus Page</a
        >
      </p>
    </div>
    <div class="d-flex flex-column me-5 text-center">
      <p>SkyHud</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/463?tab=description"
          target="_blank">Nexus Page</a
        >
      </p>
    </div>
    <div class="d-flex flex-column me-5 text-center">
      <p>Nordic UI Overhaul</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/49881?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
  </div>
  <div class="d-flex mb-5 justify-content-center">
    <div class="d-flex flex-column me-5 text-center">
      <p>Werewolf Perks Expanded</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/1285?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>Dragon Aspect (Mage Version)</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/22763?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>My home is your home</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/7096?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>Paarthurnax Quest Expansion</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/51711?tab=description"
          target="_blank">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>Cloaks of Skyrim</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/6369?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>Armor Variants Expansion</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/34100?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
  </div>
  <div class="d-flex justify-content-center">
    <div class="me-5 text-center">
      <p>Convenient Horses</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/9519?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>Sleek Wolf Armor</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/44812?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>Perk Point Book</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/2254?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>Magic Training</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/40000?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>Alternate Start - Live Another Life</p>
      <p style="color: red;">* Requires Unofficial Patch *</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/272?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
    <div class="me-5 text-center">
      <p>A Quality World Map</p>
      <p>
        <a
          href="https://www.nexusmods.com/skyrimspecialedition/mods/5804?tab=description"
          target="_blank"
          rel="noopener noreferrer">Nexus Page</a
        >
      </p>
    </div>
  </div>
</div>
<div id="guides" class="guides">
  <h2>guides</h2>

  <div class="goldbrand">
    <h4>A Matter of Pride: Goldbrand</h4>

    <ol>
      <li>Start quest:</li>
      <ul>
        <li>Boethia's Shrine = find Eranya's Journal</li>
        <li>College of Winterhold = find Eranya's Research Notes</li>
      </ul>
      <li>Find Sivdur's Amulet = Whiterun, Lars Battle-Born</li>
      <li>Find Magrathi's Skull = Ivarstead, Shroud Hearth Barrow</li>
      <li>Travel to Sivdur's Respite</li>
      <li>Locate Goldbrand</li>
    </ol>
  </div>

  <div class="shouts">
    <h4>Dragon Shouts</h4>

    <div class="d-flex">
      <div class="shout">
        <p class="fw-bold">Animal Allegiance</p>

        <ul>
          <li>
            <a href="images/ascent.jpeg" target="_blank">Ancient's Ascent</a>
          </li>
          <li>
            <a href="images/Angarvunde_Maplocation.webp" target="_blank"
              >Angarvunde</a
            >
          </li>
          <li>Ysgramor's Tomb</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Aura Whisper</p>

        <ul>
          <li>
            <a
              href="images/Northwind_summit_map.webp"
              target="_blank"
              rel="noopener noreferrer">Northwind Summit</a
            >
          </li>
          <li>
            <a href="images/Valthume_Map.webp" target="_blank">Valthume</a>
          </li>
          <li>
            <a
              href="images/Volunruudmap.webp"
              target="_blank"
              rel="noopener noreferrer">Volunruud</a
            >
          </li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Battle Fury</p>

        <ul>
          <li>
            <a href="images/Vahlok.webp" target="_blank">Vahlok's Tomb</a>
          </li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Become Ethereal</p>

        <ul>
          <li>
            <a
              href="images/Ironbind_Barrow.webp"
              target="_blank"
              rel="noopener noreferrer">Ironbind Barrow</a
            >
          </li>
          <li>
            <a
              href="images/Lost_Valley_Redoubt.webp"
              target="_blank"
              rel="noopener noreferrer">Lost Valley Redoubt</a
            >
          </li>
          <li>Ustengrav (main quest)</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Bend Will</p>

        <ul>
          <li>Dragonborn- Main Quest</li>
        </ul>
      </div>
    </div>
    <div class="d-flex">
      <div class="shout">
        <p class="fw-bold">Call Dragon</p>

        <ul>
          <li>Main Quest</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Call of Valor</p>

        <ul>
          <li>Sovngarde - Main Quest</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Clear Skies</p>

        <ul>
          <li>High Hrothgar - Main Quest</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Cyclone</p>

        <ul>
          <li>
            <a
              href="images/Benkongerike.webp"
              target="_blank"
              rel="noopener noreferrer">Benkongerike</a
            >
          </li>
          <li>
            <a href="images/Kolbjorn_Barrow_DB_Map.webp" target="_blank"
              >Kolbjorn Barrow</a
            >
          </li>
          <li>
            <a
              href="images/White_Ridge_Barrow.webp"
              target="_blank"
              rel="noopener noreferrer">White Ridge Sanctum</a
            >
          </li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Disarm</p>

        <ul>
          <li>
            <a
              href="images/Eldersblood.webp"
              target="_blank"
              rel="noopener noreferrer">Eldersblood Peak</a
            >
          </li>
          <li>
            <a
              href="images/SSilverdrift.webp"
              target="_blank"
              rel="noopener noreferrer">Silverdrift Lair</a
            >
          </li>
          <li>Snow Veil Canctum (thieves guild)</li>
        </ul>
      </div>
    </div>
    <div class="d-flex">
      <div class="shout">
        <p class="fw-bold">Dismay</p>

        <ul>
          <li>
            <a
              href="images/Dead_Crone_Rock.webp"
              target="_blank"
              rel="noopener noreferrer">Dead Crone Rock</a
            >
          </li>
          <li>
            <a
              href="images/Lost_Tongue_Overlook_Map.webp"
              target="_blank"
              rel="noopener noreferrer">Lost Tongue Overlook</a
            >
          </li>
          <li>Shalidor's Maze, Labyrinthian</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Dragon Aspect</p>

        <ul>
          <li>Raven Rock Mine</li>
          <li>Temple of Miraak</li>
          <li>Apocrypha</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Dragonrend</p>

        <ul>
          <li>Main Quest</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Drain Vitality</p>

        <ul>
          <li>
            <a
              href="images/ArcwindPointMap.webp"
              target="_blank"
              rel="noopener noreferrer">Arcwind Point</a
            >
          </li>
          <li>Dawnguard - Main Quest</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Elemental Fury</p>

        <ul>
          <li>
            <a
              href="images/Dragontooth_Crater_Map.webp"
              target="_blank"
              rel="noopener noreferrer">Dragontooth Crater</a
            >
          </li>
          <li>
            <a
              href="images/South_Shriekwind_Bastion.webp"
              target="_blank"
              rel="noopener noreferrer">Shriekwind Bastion</a
            >
          </li>
          <li>Statue of Meridia</li>
        </ul>
      </div>
    </div>
    <div class="d-flex">
      <div class="shout">
        <p class="fw-bold">Fire Breath</p>

        <ul>
          <li>Dustman's Cairn (Companion's Quest)</li>
          <li>
            <a
              href="images/Sunderstone_Gorge.webp"
              target="_blank"
              rel="noopener noreferrer">Sunderstone Gorge</a
            >
          </li>
          <li>Main Quest</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Frost Breath</p>

        <ul>
          <li>
            <a
              href="images/Skyrim_map_Bonestrewn_Crest.webp"
              target="_blank"
              rel="noopener noreferrer">Bonestrewn Crest</a
            >
          </li>
          <li>
            <a
              href="images/Folgunthur_Map.webp"
              target="_blank"
              rel="noopener noreferrer">Folgunthur</a
            >
          </li>
          <li>
            <a
              href="images/Skyborn_Altar_MAP.webp"
              target="_blank"
              rel="noopener noreferrer">Skyborn Altar</a
            >
          </li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Ice Form</p>

        <ul>
          <li>
            <a
              href="images/Frostmerecryptmap.webp"
              target="_blank"
              rel="noopener noreferrer">Frostmere Crypt</a
            >
          </li>
          <li>
            <a
              href="images/Mount_Anthor_Map.webp"
              target="_blank"
              rel="noopener noreferrer">Mount Anthor</a
            >
          </li>
          <li>Saarthal(mage's quest)</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Kyne's Peace</p>

        <ul>
          <li>
            <a
              href="images/Ragnvald.webp"
              target="_blank"
              rel="noopener noreferrer">Ragnvald</a
            >
          </li>
          <li>
            <a
              href="images/Rannveig.webp"
              target="_blank"
              rel="noopener noreferrer">Ranngeig's Fast</a
            >
          </li>
          <li>
            <a
              href="images/Shroud_Hearth_Barrow_map.webp"
              target="_blank"
              rel="noopener noreferrer">Shroud Hearth Barrow</a
            >
          </li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Marked For Death</p>

        <ul>
          <li>
            <a
              href="images/Autmnwatch_tower_Map.webp"
              target="_blank"
              rel="noopener noreferrer">Autumnwatch Tower</a
            >
          </li>
          <li>Dark Brotherhood Sanctuary</li>
          <li>
            <a
              href="images/Forsaken_Cave_Maplocation.webp"
              target="_blank"
              rel="noopener noreferrer">Forsaken Cave</a
            >
          </li>
        </ul>
      </div>
    </div>
    <div class="d-flex">
      <div class="shout">
        <p class="fw-bold">Slow Time</p>

        <ul>
          <li>
            <a
              href="images/hagsend.webp"
              target="_blank"
              rel="noopener noreferrer">Forsaken Cave</a
            >
          </li>
          <li>Korvanjund (civil war)</li>
          <li>Labyrinthian (mage's quest)</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Soul Tear</p>

        <ul>
          <li>Durnehviir</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Storm Call</p>

        <ul>
          <li>
            <a
              href="images/Forelhostmap.webp"
              target="_blank"
              rel="noopener noreferrer">Forelhost</a
            >
          </li>
          <li>
            <a
              href="images/Highgate_ruins_map.webp"
              target="_blank"
              rel="noopener noreferrer">High Gate Ruins</a
            >
          </li>
          <li>Skuldafn (main quest)</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Summon Durnehviir</p>

        <ul>
          <li>Soul Cairn</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Throw Voice</p>

        <ul>
          <li>
            <a
              href="images/Shearpoint_Location.webp"
              target="_blank"
              rel="noopener noreferrer">Shearpoint</a
            >
          </li>
        </ul>
      </div>
    </div>
    <div class="d-flex">
      <div class="shout">
        <p class="fw-bold">Unrelenting Force</p>

        <ul>
          <li>Main Quest</li>
        </ul>
      </div>
      <div class="shout">
        <p class="fw-bold">Whirlwind Sprint</p>

        <ul>
          <li>
            <a
              href="images/respite.webp"
              target="_blank"
              rel="noopener noreferrer">Dead Men's Respite</a
            >
          </li>
          <li>Main Quest</li>
          <li>
            <a
              href="images/Volskygge_Maplocation.webp"
              target="_blank"
              rel="noopener noreferrer">Volskygge</a
            >
          </li>
        </ul>
      </div>
    </div>
  </div>

  <div class="priests text-center">
    <h4>Dragon Priest Masks</h4>

    <div class="d-flex">
      <div class="d-flex flex-column ms-5 me-5">
        <p>Hevnoraak = Valthume</p>
        <a href="images/Valthume_Map.webp" target="_blank"
          ><img src="images/Valthume_Map.webp" alt="mask" /></a
        >
      </div>

      <div class="d-flex flex-column">
        <p>Krosis = Shearpoint</p>
        <a href="images/Shearpoint_Location.webp" target="_blank"
          ><img src="images/Shearpoint_Location.webp" alt="mask" /></a
        >
      </div>
    </div>
    <div class="d-flex align-items-center">
      <div class="d-flex flex-column ms-5 me-5">
        <p>Moroei = Labyrinthian</p>
        <a href="images/Labyrinthian_Map.webp" target="_blank">
          <img src="images/Labyrinthian_Map.webp" alt="mask" /></a
        >
      </div>

      <p>Nahkriin = Skuldafn, Main Quest</p>
    </div>
    <div class="d-flex">
      <div class="d-flex flex-column ms-5 me-5">
        <p>Otar = Ragnvald</p>
        <a href="images/Ragnvald_Dungeon_-_Overland_Map.webp" target="_blank">
          <img src="images/Ragnvald_Dungeon_-_Overland_Map.webp" alt="mask" />
        </a>
      </div>
      <div class="d-flex flex-column">
        <p>Rahgot = Forelhost</p>
        <a href="images/Forelhostmap.webp" target="_blank"
          ><img src="images/Forelhostmap.webp" alt="mask" /></a
        >
      </div>
    </div>

    <div class="d-flex">
      <div class="d-flex flex-column ms-5 me-5">
        <p>Vokun = High Gate Ruins</p>
        <a href="images/Highgate_ruins_map.webp" target="_blank"
          ><img src="images/Highgate_ruins_map.webp" alt="mask" /></a
        >
      </div>

      <div class="flex-column">
        <p>Volsung = Volskygge</p>
        <a href="images/Volskygge_Maplocation.webp" target="_blank">
          <img src="images/Volskygge_Maplocation.webp" alt="mask" />
        </a>
      </div>
    </div>
    <h4>Dragonborn: Masks</h4>

    <div class="d-flex">
      <div class="flex-column ms-5 me-5">
        <p>Ahzidal = Kolbjorn Barrow</p>
        <a href="images/Kolbjorn_Barrow_DB_Map.webp" target="_blank"
          ><img src="images/Kolbjorn_Barrow_DB_Map.webp" alt="mask" /></a
        >
      </div>

      <div class="flex-column">
        <p>Dulkaan = White Ridge Barrow</p>
        <a href="images/White_Ridge_Barrow.webp" target="_blank"
          ><img src="images/White_Ridge_Barrow.webp" alt="mask" /></a
        >
      </div>
    </div>

    <p>Zahkriisos = Bloodskal Barrow, in Raven Rock Mine</p>
    <p>Miraak = Main Quest</p>
  </div>
</div>
