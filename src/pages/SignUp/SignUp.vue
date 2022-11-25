<template>
    <nav class="bg-[#ACC2FE] h-[80px]">
      <div class="max-w-7xl mx-auto px-2 py-2">
        <div class="flex justify-between">
          <!-- logo -->
          <div>
            <img src="@/assets/logo-markon.png" alt="logo" class="" />
          </div>
  
          <!-- button -->
          <div class="hidden md:flex items-center space-x-3">
            <button
              type="button"
              class="
                border-2 border-[#F9D030]
                bg-transparent
                py-2
                px-3
                rounded
                transition
                duration-300
              "
            >
              Sign Up
            </button>
            <button
              type="button"
              class="
                py-2
                px-3
                bg-yellow-400
                hover:bg-yellow-300
                text-yellow-900
                hover:text-yellow-800
                rounded
                transition
                duration-300
              "
            >
              Sign In
            </button>
          </div>
        </div>
      </div>
    </nav>
  
    <!-- content -->
    <div
      class="
        max-w-6xl
        mx-auto
        px-2
        py-2
        my-10
        border-2 border-solid border-[#C1BFC3]
        rounded-3xl
      "
    >
      <div class="flex justify-start">
        <!-- image -->
        <div>
          <img src="@/assets/Checklist.png" alt="logo" class="" />
        </div>
  
        <!-- form -->
        <div
          class="
            max-w-sm
            my-8
            mx-8
            rounded
            overflow-hidden
            shadow-xl
            border-2 border-solid border-[#C1BFC3]
          "
        >
          <!-- <img
            class="w-full"
            src="/img/card-top.jpg"
            alt="Sunset in the mountains"
          /> -->
          <div class="px-6 py-4">
            <div class="text-center font-medium text-base mb-2">
              Daftar di <span class="font-bold text-blue-600">Markon</span>
            </div>
            <!-- <div class="font-bold text-xl mb-2">The Coldest Sunset</div> -->
            <p class="text-gray-700 text-base">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit.
              Voluptatibus quia, nulla! Maiores et perferendis eaque,
              exercitationem praesentium nihil.
            </p>
          </div>
          <!-- <div class="px-6 pt-4 pb-2">
            <span
              class="
                inline-block
                bg-gray-200
                rounded-full
                px-3
                py-1
                text-sm
                font-semibold
                text-gray-700
                mr-2
                mb-2
              "
              >#photography</span
            >
            <span
              class="
                inline-block
                bg-gray-200
                rounded-full
                px-3
                py-1
                text-sm
                font-semibold
                text-gray-700
                mr-2
                mb-2
              "
              >#travel</span
            >
            <span
              class="
                inline-block
                bg-gray-200
                rounded-full
                px-3
                py-1
                text-sm
                font-semibold
                text-gray-700
                mr-2
                mb-2
              "
              >#winter</span
            >
          </div> -->
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    setup() {
      return {};
    },
  };
  </script>
  
  <style lang="scss" scoped></style>
  