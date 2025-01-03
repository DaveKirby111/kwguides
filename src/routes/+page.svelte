<script>
  import ttg from "$lib/images/TTG.png";
  import { pageTitle } from "$lib/stores.js";
  pageTitle.set("KWorld Game Guides");

  const games = [
    {
      title: "assassin's creed",
      games: [
        {
          title: "assassin's creed 2,  ",
          url: "/ac2",
        },
        {
          title: "odyssey",
          url: "/odyssey",
        },
      ],
    },
    {
      title: "deus ex",
      games: [
        {
          title: "human revolution,  ",
          url: "/hr",
        },

        {
          title: "mankind divided",
          url: "/md",
        },
      ],
    },
    {
      title: "dragon age",
      games: [
        {
          title: "DA Origins,  ",
          url: "/da1",
        },

        {
          title: "DA II,  ",
          url: "/da2",
        },

        {
          title: "DA Inquisition",
          url: "/da3",
        },
      ],
    },

    {
      title: "elder scrolls",
      games: [
        {
          title: "morrowind,  ",
          url: "/morrowind",
        },

        {
          title: "oblivion,  ",
          url: "/oblivion",
        },

        {
          title: "skyrim, ",
          url: "/skyrim",
        },

        {
          title: "enderal",
          url: "/enderal",
        },
      ],
    },

    {
      title: "fallout",
      games: [
        {
          title: "fallout 4, ",
          url: "/fallout4"
        },

        {
          title: "falloutNV",
          url: "/nvegas"
        },
      ],
    },


    {
      title: "final fantasy",
      games: [
        {
          title: "VII,  ",
          url: "/ff7",
        },

        {
          title: "VIII,  ",
          url: "/ff8",
        },

        {
          title: "IX,  ",
          url: "/ff9",
        },

        {
          title: "XII,  ",
          url: "/ff12",
        },

        {
          title: "XIII,  ",
          url: "/ff13",
        },

        {
          title: "XV, ",
          url: "/ff15",
        },

        {
          title: "Crisis Core",
          url: "/ccore",
        },
      ],
    },
    {
      title: "mass effect",
      games: [
        {
          title: "mass effect,  ",
          url: "/me1",
        },

        {
          title: "mass effect 2,  ",
          url: "/me2",
        },

        {
          title: "mass effect 3",
          url: "/me3",
        },
      ],
    },
    {
      title: "resident evil",
      games: [
        {
          title: "RE 1 Remake,  ",
          url: "/re1",
        },

        {
          title: "RE 2 Remake,  ",
          url: "/re2",
        },

        {
          title: "RE 3 Remake, ",
          url: "/re3",
        },

        {
          title: "RE 4 Remake",
          url: "/re4",
        },
      ],
    },

    {
      title: "tomb raider",
      games: [
        {
          title: "tomb raider,  ",
          url: "/traider",
        },

        {
          title: "rise of the tomb raider,  ",
          url: "/rise",
        },

        {
          title: "shadow of the tomb raider",
          url: "/shadow",
        },
      ],
    },

    {
      title: "witcher",
      games: [
        {
          title: "witcher 2,  ",
          url: "/witcher2",
        },

        {
          title: "witcher 3",
          url: "/witcher3",
        },
      ],
    },
  ];
</script>

<div class="page-img">
  <img src={ttg} alt="ttg" class="ttg" />
</div>

<div class="games">
  <table
    class="table table-borderless table-dark table-striped table-responsive text-capitalize"
  >
    <thead>
      <tr>
        <th>title</th>
        <th>games</th>
      </tr>
    </thead>
    <tbody>
      {#each games as game}
        <tr>
          <td>{game.title}</td>
          <td>
            {#each game.games as entry}
              <a href={entry.url}>{entry.title}</a>
            {/each}
          </td>
        </tr>
      {/each}
    </tbody>
  </table>
</div>

<style>
  table {
    table-layout: fixed;
    margin-bottom: 0;
  }

  img,
  div {
    margin-bottom: 0;
  }
</style>
