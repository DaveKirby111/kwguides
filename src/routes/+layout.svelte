<script>
  import "$lib/app.css";
  import Header from "$lib/header.svelte";
  import Footer from "$lib/footer.svelte";
</script>

<svelte:head>
  <title>KWorld Game Guides</title>

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

<div class="container-fluid d-flex flex-column min-vh-100 m-0 p-0 flex-wrap">
  <Header />

  <main class="flex-grow-1">
    <slot />
  </main>

  <Footer />
</div>
