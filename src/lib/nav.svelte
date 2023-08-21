<script>
  import { links } from "./nav.js";
</script>

<nav class="navbar navbar-expand-sm ms-auto">
  <div class="container-fluid">
    <ul class="navbar-nav text-capitalize">
      {#each links as link}
        <li class="nav-item" id={link.id}>
          <a
            href={link.url}
            class="nav-link dropdown-toggle"
            role="button"
            data-bs-toggle="dropdown">{link.title}</a
          >
          <ul class="dropdown-menu p-0">
            {#each link.subitems as subitem}
              <li>
                <a href={subitem.url} class="dropdown-item">{subitem.page}</a>
              </li>
            {/each}
          </ul>
        </li>
      {/each}
    </ul>
  </div>
</nav>
