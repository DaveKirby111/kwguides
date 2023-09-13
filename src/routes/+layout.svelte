<script>
  import "$lib/app.css";
  import "$lib/screen.css";
  import Header from "$lib/header.svelte";
  import Footer from "$lib/footer.svelte";
  import { pageTitle } from "$lib/stores.js";
</script>

<svelte:head>
  <title>{$pageTitle}</title>

  <script>
    $(document).ready(function () {
      $(".dropdown").hover(
        function () {
          $(this).addClass("show");
          $(this).find(".dropdown-menu").addClass("show");
        },
        function () {
          $(this).removeClass("show");
          $(this).find(".dropdown-menu").removeClass("show");
        }
      );
    });
  </script>
</svelte:head>

<div class="container-fluid d-flex flex-column min-vh-100 m-0 p-0">
  <Header />

  <main class="flex-grow-1">
    <slot />
  </main>

  <Footer />
</div>
