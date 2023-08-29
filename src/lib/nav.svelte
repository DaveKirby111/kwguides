<script>
  import { links } from "./nav.js";
</script>

<nav class="navbar navbar-expand-sm ms-auto">
  <ul class="navbar-nav text-capitalize">
    {#each links as link}
      <li class="nav-item dropdown" id={link.id}>
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
</nav>

<style>
  nav ul {
    margin-right: 20px;
    text-align: center;
  }

  nav ul li a {
    width: 200px;
  }

  .dropdown-menu {
    text-align: center;
  }

  .dropdown:hover .dropdown-menu {
    display: block;
  }

  .dropdown-menu li {
    border-bottom: 1px solid lightgray;
  }

  .dropdown-menu li:last-child {
    border-bottom: none;
  }
</style>
