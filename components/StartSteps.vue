<template>
  <main
    style="background-color: #101828"
    class="lg:flex lg:px-32 py-10 lg:py-40 lg:space-x-10 relative"
  >
    <div class="hidden lg:flex justify-end items-end absolute right-0 top-0">
      <img src="@/assets/images/triangle.svg" alt="" />
    </div>
    <div class="hidden lg:flex justify-end items-end absolute right-0 top-0">
      <img src="@/assets/images/arrowDownard.svg" alt="" />
    </div>
    <div class="hidden lg:flex justify-end items-end absolute left-0 bottom-0">
      <img src="@/assets/images/arrowMask.svg" alt="" />
    </div>
    <div class="lg:w-1/2 space-y-16">
      <div>
        <div class="space-y-9 px-6 lg:px-0">
          <h1 style="color: #47bfa3" class="text-3xl font-mono">
            Everything you need to start building
          </h1>
          <p class="font-semibold text-white font-mono leading-loose">
            We understand the crux of good developer experience while
            interfacing with an API. Our developer-friendly guide will get you
            started in no time.
          </p>
          <button
            style="background-color: #47bfa3"
            class="text-white px-6 py-3 rounded-md"
          >
            Read the docs
          </button>
        </div>
      </div>
      <div
        style="background-color: #1d2939"
        class="rounded-md shadow-md lg:p-10 p-6 space-y-10 mx-7 lg:mx-0"
      >
        <div class="flex items-start gap-2">
          <div class="">
            <img class="h-6 w-6" src="@/assets/images/ellipse.svg" alt="" />
          </div>

          <div>
            <h2 class="text-lg font-bold font-mono text-white">APIs</h2>

            <p class="mt-1 font-light text-gray-200 text-sm lg:text-base">
              Seamless API integrations designed to optimised user’s experience.
            </p>
          </div>
        </div>

        <div class="flex items-start gap-2">
          <div class="">
            <img class="h-6 w-6" src="@/assets/images/ellipse.svg" alt="" />
          </div>

          <div>
            <h2 class="text-lg font-bold font-mono text-white">SDKs</h2>

            <p class="mt-1 font-light text-gray-200 text-sm lg:text-base">
              Customizable SDKs that plays nicely with your infrastructure.
            </p>
          </div>
        </div>

        <div class="flex items-start gap-2">
          <div class="">
            <img class="h-6 w-6" src="@/assets/images/ellipse.svg" alt="" />
          </div>

          <div>
            <h2 class="text-lg font-bold font-mono text-white">Claims</h2>

            <p class="mt-1 font-light text-gray-200 text-sm lg:text-base">
              Reliably automate claims assessment with real-time data inputs,
              enabled by our API.
            </p>
          </div>
        </div>
      </div>
    </div>

    <div class="lg:w-1/2">
      <div class="lg:rounded-md lg:shadow-md space-y-6 p-6 lg:p-0">
        <div
          class="flex justify-center items-center flex-col p-3 lg:p-16 shadow-md rounded-md"
          style="background-color: #1d2939"
        >
          <img src="@/assets/images/paymentLogo.svg" alt="" />

          <form
            action=""
            class="mt-6 mb-0 space-y-10 rounded-sm p-6 w-full bg-white"
          >
            <div class="space-y-3">
              <label style="color: #344054" for="email" class="text-sm"
                >Name of Plan Owner</label
              >

              <div class="relative">
                <input
                  type="text"
                  class="w-full border-gray-200 p-4 pr-12 text-sm ring-1 ring-gray-100 rounded-md"
                  placeholder="First Name, Last Name"
                />
              </div>
            </div>

            <div class="space-y-3">
              <label style="color: #344054" for="password" class="text-sm"
                >Email</label
              >

              <div class="relative">
                <input
                  type="email"
                  class="w-full border-gray-200 p-4 pr-12 text-sm ring-1 ring-gray-100 rounded-md"
                  placeholder="Enter email address"
                />
              </div>
            </div>

            <button
              style="background-color: #e18c2f"
              type="submit"
              class="block w-full rounded-lg px-5 py-3 text-sm font-medium text-white"
            >
              Continue
            </button>

            <div class="flex justify-center items-center space-x-2 py-3">
              <p class="text-center text-sm text-gray-500">Underwritten by</p>
              <img src="@/assets/images/hygeia.svg" alt="" />
            </div>
          </form>

          <p class="text-center text-white pt-6">
            <span class="text-gray-400">Powered by</span> Mycover.ai
          </p>
        </div>
        <div class="">
          <img src="@/assets/images/api.svg" alt="" />
        </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {};
</script>

<style>
</style>