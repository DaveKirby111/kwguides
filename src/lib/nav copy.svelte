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

  .dropdown-item:hover {
    background-color: green;
    text-shadow: 2px 2px 2px black;
  }

  .dropdown {
    width: 100%;
  }

  .dropdown a {
    color: rgb(0, 176, 0);
  }

  .dropdown-menu {
    text-align: center;
    /* background: rgba(0, 0, 0, 0.1); */
    background-color: black;
  }

  .dropdown:hover .dropdown-menu {
    display: block;
  }

  .dropdown-menu li {
    border-bottom: 1px solid rgb(0, 176, 0);
  }

  .dropdown-menu li:last-child {
    border-bottom: none;
  }

  @media screen and (max-width: 600px) {
    nav ul {
      width: 100%;
    }

    .dropdown {
      width: 100%;
    }
  }

  @media screen and (max-width: 900px) {
    nav ul {
      width: 100%;
      flex-direction: column;
    }

    .dropdown {
      width: 100%;
    }
  }
</style>
