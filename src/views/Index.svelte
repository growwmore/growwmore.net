<script>
  // import { Router, Route } from "svelte-routing";
  import { link } from "svelte-routing";
  // components for this layout
  import AuthNavbar from "components/Navbars/AuthNavbar.svelte";
  import FooterSmall from "components/Footers/FooterSmall.svelte";

  // pages for this layout
  import Login from "views/auth/Login.svelte";

  const registerBg2 = "../assets/img/register_bg_1.png";
  // core components
  const logo = "/assets/img/gm_logo.svg";
  const github = "/assets/img/github.svg";
</script>

<!-- <script>
  import { link } from "svelte-routing";

  // core components
  const logo = "/assets/img/gm_logo.svg";
  const github = "/assets/img/github.svg";
  const google = "/assets/img/google.svg";
  export let location;
</script> -->

<div>
  <AuthNavbar />
  <main>
    <section class="relative w-full h-full py-40 min-h-screen">
      <div
        class="absolute top-0 w-full h-full bg-green-200 bg-no-repeat bg-full"
        style="background-image: url({registerBg2});"
      ></div>
      <section class="header relative pt-0 mt-25 max-h-860-px">
        <div class="container center mx-auto px-4 h-full">
          <div class="w-full md:w-6/12 mx-auto lg:w-6/12 xl:w-6/12 px-4">
            <!-- <div class="pt-12 sm:pt-0"> -->
              <img class="relative top-0 b-auto center" src="{logo}" alt=".." />
              <h2 class="font-semibold text-center text-4xl text-black" style="font-family: Matryoshka">
                GROWWMORE<sup>©</sup>
              </h2>
              <h4 class="font-semibold text-center text-2xl text-white">
                Investing is for everyone. We're here to help you
              </h4>
            <!-- </div> -->
          </div>
        </div>
      </section>
      <FooterSmall absolute="true" />
    </section>
  </main>
</div>


