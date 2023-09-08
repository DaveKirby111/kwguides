<script>
  export let sections = [];
</script>

<div class="sections text-capitalize">
  <ul class="nav justify-content-center">
    {#each sections as section}
      <li class="nav-item">
        <a href={section.link} class="skiplink nav-link">{section.name}</a>
      </li>
    {/each}
  </ul>
</div>

<style>
  .sections {
    background-image: url("$lib/images/space.webp");
    background-size: 100% 100%;
  }

  .sections li a {
    color: rgb(0, 176, 0);
  }

  @media screen and (max-width: 600px) {
    ul li {
      text-align: center;
    }
  }

  @media screen and (max-width: 900px) {
    .sections ul {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }

    .sections li {
      text-align: center;
      flex: 0 0 33.33%;
      margin: 10px;
    }
  }
</style>
