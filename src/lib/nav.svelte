<script>
  import { links } from "./nav.js";

  let isMobileMenuOpen = false;

  function toggleMobileMenu() {
    isMobileMenuOpen = !isMobileMenuOpen;
  }
</script>

<nav class="navbar d-flex justify-content-center p-0">
  <!-- Hamburger Menu Button -->
  <button class="hamburger" on:click={toggleMobileMenu}>
    <svg
      xmlns="http://www.w3.org/2000/svg"
      fill="none"
      viewBox="0 0 24 24"
      stroke-width="1.5"
      stroke="currentColor"
      class="w-6 h-6"
    >
      <path
        stroke-linecap="round"
        stroke-linejoin="round"
        d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5"
      />
    </svg>
  </button>

  <!-- Navigation Links -->
  <ul class="navbar-nav text-capitalize" class:open={isMobileMenuOpen}>
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
    width: 250px;
    background-color: black;
  }

  /* .dropdown:hover .dropdown-menu {
    display: block;
  } */

  .dropdown-menu li {
    border-bottom: 1px solid rgb(0, 176, 0);
  }

  .dropdown-menu li:last-child {
    border-bottom: none;
  }

  .hamburger {
    /* display: none; */
    cursor: pointer;
    padding: 10px;
    background: transparent;
    border: none;
    outline: none;
    z-index: 1000;
    /* margin-left: auto;  */
    margin-top: 20px;
  }

  .hamburger svg {
    height: 60px;
    color: rgb(0, 176, 0);
  }

  .navbar-nav {
    display: none;
  }

  .navbar-nav.open {
    display: block;
    margin-bottom: 20px;
  }

  @media screen and (max-width: 600px) {
    nav ul {
      width: 100%;
    }

    .dropdown {
      width: 100%;
    }

    .hamburger {
      display: block;
    }

    .navbar-nav {
      display: none;
    }

    .navbar-nav.open {
      display: flex;
      flex-direction: column;
      text-align: center;
      width: 100%;
    }
  }

  @media screen and (max-width: 900px) {
    nav ul {
      width: 100%;
      flex-direction: column;
    }

    nav {
      flex-direction: column;
    }

    .dropdown {
      width: 100%;
    }

    .hamburger {
      display: block;
    }

    .navbar-nav {
      display: none;
    }

    .navbar-nav.open {
      display: flex;
      flex-direction: column;
      text-align: center;
      width: 100%;
    }
  }
</style>
