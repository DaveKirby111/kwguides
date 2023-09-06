<script>
  import { links } from "./nav.js";
</script>

<nav class="navbar navbar-expand-sm d-flex justify-content-center p-0">
  <ul class="navbar-nav text-capitalize">
    {#each links as link}
      <li class="nav-item dropdown" id={link.id}>
        <a
          href={link.url}
          class="nav-link dropdown-toggle mb-3 mb-md-0"
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
    margin: auto;
    text-align: center;
    width: 100%;
  }

  .nav-item:hover {
    text-decoration: underline;
  }

  .dropdown {
    border: 2px solid black;
    width: 100%;
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

  @media screen and (max-width: 400px) {
    nav ul {
      width: 100%;
    }

    .dropdown {
      width: 100%;
    }
  }
</style>
