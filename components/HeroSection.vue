<template>
  <main class="relative">
    <div class="hidden lg:flex justify-end items-end z-50 absolute right-0">
      <img src="@/assets/images/verticalDots.svg" alt="" />
    </div>
    <section class="overflow-hidden bg-gray-50 lg:flex justify-between">
      <div class="p-8 md:p-12 lg:px-16 lg:py-24">
        <div class="mx-auto max-w-xl text-center sm:text-left">
          <h2
            class="bg-gradient-to-r from-black via-green-500 to-black bg-clip-text text-transparent text-5xl font-bold md:text-6xl"
          >
            Revolutionizing the insurance experience in Africa
          </h2>

          <p class="text-gray-500 md:mt-4 md:block pt-6 lg:pt-0">
            Our Open Insurance API enables businesses and innovators easily
            embed or build new insurtech solutions to distribute insurance to
            anyone, from anywhere.
          </p>

          <div
            class="w-full mt-4 md:mt-8 lg:space-x-10 space-y-6 lg:space-y-0 lg:flex items-center"
          >
            <div
              style="background-color: #47bfa3"
              href="#"
              class="space-x-3 text-white flex justify-center items-center rounded bg-gray-200 px-12 py-3 text-sm font-medium ring-1 ring-gray-200 transition focus:outline-none focus:ring focus:ring-yellow-400"
            >
              <p>Get Started</p>
            </div>

            <div
              style="background-color: #f2f4f7"
              href="#"
              class="space-x-3 flex justify-center items-center rounded bg-gray-200 px-12 py-3 text-sm font-medium ring-1 ring-gray-200 transition focus:outline-none focus:ring focus:ring-yellow-400"
            >
              <p>View Demo</p>

              <img src="@/assets/images/videoIcon.svg" alt="" />
            </div>
          </div>
        </div>
      </div>

      <div>
        <img
          alt="Student"
          src="@/assets/images/heroImage.svg"
          class="h-56 w-full object-cover sm:h-full"
        />
      </div>
    </section>
    <div
      class="bg-gray-50 w-full space-x-96 hidden lg:flex items-center mt-0 pt-0 absolute -bottom-20"
    >
      <div><img src="@/assets/images/arrows.svg" alt="" class="" /></div>
      <div>
        <img src="@/assets/images/horizontalDots.svg" alt="" class="" />
      </div>
    </div>
  </main>
</template>

<script>
export default {};
</script>

<style>
</style>