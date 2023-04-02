<template>
  <main>
    <header aria-label="Site Header" class="shadow-sm">
      <div class="mx-auto max-w-screen-xl p-4">
        <div class="flex items-center justify-between gap-4 lg:gap-10">
          <div class="flex lg:w-0 lg:flex-1">
            <a href="#">
              <span class="sr-only">Logo</span>
              <img src="@/assets/images/logo.svg" alt="logo" />
            </a>
          </div>

          <nav
            aria-label="Site Nav"
            class="hidden gap-8 text-sm font-medium md:flex"
          >
            <a class="text-gray-500 text-xs" href="">Products</a>
            <a class="text-gray-500 text-xs" href="">Solutions</a>
            <a class="text-gray-500 text-xs" href="">Developers</a>
            <a class="text-gray-500 text-xs" href="">Company</a>
            <a class="text-gray-500 text-xs" href="">Learn</a>
          </nav>

          <div class="hidden flex-1 items-center justify-end gap-4 sm:flex">
            <a
              class="rounded-lg bg-gray-100 py-2.5 px-5 text-sm font-medium text-gray-500"
              href=""
            >
              Login
            </a>

            <a
              class="rounded-lg md:hidden lg:block bg-teal-600 hover:bg-teal-700 transition py-2.5 px-5 text-sm font-medium text-white"
              href=""
            >
              Get Started
            </a>
          </div>

          <div class="lg:hidden">
            <button
              class="rounded-lg bg-gray-100 p-2 text-gray-600"
              type="button"
            >
              <span class="sr-only">Open menu</span>
              <svg
                aria-hidden="true"
                class="h-5 w-5"
                fill="none"
                stroke="currentColor"
                viewbox="0 0 24 24"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M4 6h16M4 12h16M4 18h16"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                />
              </svg>
            </button>
          </div>
        </div>
      </div>
    </header>
    <hero-section></hero-section>
    <sponsors></sponsors>
    <div class="hidden lg:flex justify-end items-end">
      <div class="w-2/12 bg-black py-3"></div>
    </div>
    <innovations></innovations>
    <div class="hidden lg:flex justify-start items-start bg-gray-50">
      <div style="background-color: #1849a9" class="w-2/12 py-3"></div>
    </div>
    <sectors></sectors>
    <manage-section></manage-section>
    <start-steps></start-steps>
    <business-model></business-model>
    <all-in-one-solution></all-in-one-solution>
    <support-brands></support-brands>
    <footer-component></footer-component>
  </main>
</template>

<script>
import HeroSection from "@/components/HeroSection.vue";
import Sponsors from "@/components/Sponsors.vue";
import Innovations from "@/components/Innovations.vue";
import Sectors from "@/components/Sectors.vue";
import FooterComponent from "@/components/FooterComponent.vue";
import SupportBrands from "@/components/SupportBrands.vue";

import ManageSection from "@/components/ManageSection.vue";
import BusinessModel from "@/components/BusinessModel.vue";
import StartSteps from "@/components/StartSteps.vue";
import AllInOneSolution from "@/components/AllInOneSolution.vue";
// import GetStarted from "@/components/GetStarted.vue";
export default {
  components: {
    HeroSection,
    Sponsors,
    Innovations,
    Sectors,
    FooterComponent,
    SupportBrands,
    ManageSection,
    BusinessModel,
    StartSteps,
    AllInOneSolution,
    // GetStarted,
  },
};
</script>,
    StartSteps 

<style scoped>
.cta_parent {
  display: flex;
}
.cta_text {
  font-size: calc(64px + (46 * ((100vw - 375px) / 1225)));
  line-height: 100%;
  font-family: Instagram Sans, Helvetica Neue, Helvetica, Arial, sans-serif;
}

.cta_image {
  transform: scale(1.2) translate(-5px, 11px);
  transform: translateY(0);
  min-width: 28.571vw;
  height: 100%;
  object-fit: cover;
  width: 100%;
  transform: scale(1.2) translate(-5px, 11px);

  height: auto;
  max-width: 100%;
  transition: opacity 750ms cubic-bezier(0.645, 0.045, 0.355, 1);
}

.gradient_text {
  background-image: linear-gradient(
    72.44deg,
    #ff0169 4.69%,
    #d300c5 48.96%,
    #7638fa 92.19%
  );

  -webkit-background-clip: text;
  background-repeat: no-repeat;
  color: transparent;
  display: inline;
}

.animated_arrow {
  animation: verticalAnimation 2.5s infinite cubic-bezier(0, 0, 0.1, 1);
  display: block;
  width: 75px;
}

.animated_parent {
  align-items: flex-end;
  display: flex;
  height: 100px;
  left: -7.142vw;
  overflow: hidden;
  position: absolute;
}

.imageDimensions {
  width: 100%;
  height: auto;
  object-fit: cover;
}
</style>