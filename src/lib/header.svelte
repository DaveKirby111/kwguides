<script>
  import kwg from "$lib/images/kwguides.jpg";
  import Title from "$lib/title.svelte";
  import { links } from "$lib/nav.js";

  let isMobileMenuOpen = false;

  export function toggleMobileMenu() {
    isMobileMenuOpen = !isMobileMenuOpen;
  }
</script>

<div class="overlay" class:open={isMobileMenuOpen}>
  <nav class="navbar p-0">
    <ul class="navbar-nav text-capitalize" class:open={isMobileMenuOpen}>
      <li><button on:click={toggleMobileMenu}>X</button></li>
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
                <a
                  href={subitem.url}
                  class="dropdown-item"
                  on:click={toggleMobileMenu}>{subitem.page}</a
                >
              </li>
            {/each}
          </ul>
        </li>
      {/each}
    </ul>
  </nav>
</div>

<header id="top">
  <a href="/"><img src={kwg} alt="logo" class="logo" /></a>

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
</header>

<div class="page">
  <Title />
</div>

<style>
  nav {
    margin-left: auto;
    width: 100%;
  }

  nav ul {
    margin: auto;
    text-align: center;
    width: 100%;
  }

  .nav-item {
    margin-bottom: 20px;
  }

  nav button {
    background-color: rgba(0, 0, 0, 0);
    color: white;
    border: none;
    font-size: 40px;
    display: block;
    margin-left: auto;
    margin-right: 30px;
    margin-top: 10px;
  }

  nav a {
    font-size: 30px;
  }

  .dropdown-item:hover {
    background-color: rgba(0, 0, 0, 0);
  }

  .dropdown-item {
    font-size: 20px;
  }

  .dropdown {
    width: 100%;
  }

  .dropdown a {
    color: rgb(0, 176, 0);
  }

  .dropdown-menu {
    text-align: center;
    width: 100%;
    margin-bottom: 30px;
    background-color: rgba(0, 0, 0, 0);
  }

  .navbar-nav {
    display: none;
  }

  .navbar-nav.open {
    display: block;
    position: absolute;
    background-color: rgba(0, 0, 0, 0.8);
    margin-bottom: 20px;
    top: 0;
    z-index: 1;
  }

  .logo {
    width: 200px;
    height: 90px;
    margin-left: 10px;
    margin-top: 10px;
  }

  .overlay {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.8);
    display: none;
    z-index: 1;
  }

  .overlay.open {
    display: block;
    position: absolute;
    z-index: 1000;
  }

  .hamburger {
    cursor: pointer;
    padding: 10px;
    background: transparent;
    border: none;
    outline: none;
    margin-left: auto;
  }

  .hamburger svg {
    height: 60px;
    color: rgb(0, 176, 0);
  }

  .logo:hover {
    box-shadow: 5px 5px 5px red;
  }

  header {
    background-image: url("$lib/images/space.webp");
    background-size: 100% 100%;
    display: flex;
  }

  .page {
    background-color: rgb(0, 206, 0);
  }

  @media screen and (max-width: 600px) {
    header {
      padding: 10px;
    }

    .logo {
      display: block;
      margin: auto;
    }
  }

  @media screen and (max-width: 900px) {
    header {
      flex-direction: column !important;
    }
  }
</style>
