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
