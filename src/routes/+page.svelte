<script>
  import ttg from "$lib/images/TTG.png";
  import { pageTitle } from "$lib/stores.js";
  $pageTitle = "KWorld game guides";

  const games = [
    {
      title: "assassin's creed",
      games: "odyssey",
    },

    {
      title: "deus ex",
      games: "human revolution, mankind divided",
    },

    {
      title: "dragon age",
      games: "DA Origins, DA 2, DA Inquisition",
    },

    {
      title: "elder scrolls",
      games: "morrowind, oblivion, skyrim",
    },

    {
      title: "final fantasy",
      games: "VII, VIII, IX, XII, XIII, XV",
    },

    {
      title: "mass effect",
      games: "mass effect, mass effect 2, mass effect 3",
    },

    {
      title: "resident evil",
      games: "RE 1 remake, RE 2 remake, RE 3 remake",
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
          <td>{game.games}</td>
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
