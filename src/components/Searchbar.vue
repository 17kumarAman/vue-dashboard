<template>
  <div
    class="flex justify-between items-center bg-white rounded-lg p-2 shadow-lg text-sm"
  >
    <!-- Search Box -->
    <div class="bg-white rounded-lg flex items-center gap-2 p-2">
      <img src="../assets/Test/search.svg" alt="Search Icon" class="h-4 w-4" />
        <input type="text" class="text-sm text-gray-500 no-underline focus:outline-none w-full" placeholder="Search">
      
    </div>

    <!-- Right Section with gap between elements -->
    <div class="flex items-center gap-5">
      <!-- Profile Box -->
      <div
        class="text-[#800080] bg-[#F2E6F2] flex items-center gap-3 p-2 rounded-lg"
      >
        <svg
          data-slot="icon"
          fill="none"
          stroke-width="1.5"
          stroke="currentColor"
          viewBox="0 0 24 24"
          xmlns="http://www.w3.org/2000/svg"
          aria-hidden="true"
          class="h-4 w-4"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="m11.25 11.25.041-.02a.75.75 0 0 1 1.063.852l-.708 2.836a.75.75 0 0 0 1.063.853l.041-.021M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0Zm-9-3.75h.008v.008H12V8.25Z"
          ></path>
        </svg>
        <span>Complete your profile</span>
        <span class="font-bold underline cursor-pointer">Let's Go</span>
      </div>

      <!-- Board Box -->
      <div class="bg-[#F7F7F7] flex items-center gap-3 p-2 rounded-lg">
        <img
          src="../assets/Test/kanban 1.svg"
          alt="Board Icon"
          class="h-4 w-4"
        />
        <span>Board</span>
      </div>

      <!-- Notifications and Icons Box -->
      <div class="bg-[#F7F7F7] flex items-center gap-3 p-2 rounded-lg">
        <img
          src="../assets/Test/notofication copy.svg"
          alt="Notification Icon"
          class="h-4 w-4"
        />|
        <img
          src="../assets/Test/question 1.svg"
          alt="Question Icon"
          class="h-4 w-4"
        />|
        <img
          src="../assets/Test/thumbs-up-trust 1.svg"
          alt="Thumbs Up Icon"
          class="h-4 w-4"
        />
      </div>

      <!-- Profile Box -->
      <div class="flex items-center gap-3 rounded-lg justify-center">
        <img
          src="../assets/Test/bd99690039f35eb8f13e58adae118810.png"
          alt="Profile Image"
          class="rounded-full h-10 w-10"
        />
        <div class="flex flex-col">
          <h1 class="text-sm font-semibold">Aman</h1>
          <h2 class="text-xs text-gray-500 font-semibold">Customer</h2>
        </div>
        <div class="bg-[#800080] rounded-full">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 24 24"
            fill="currentColor"
            class="size-6 font-bold m-1 text-white"
          >
            <path
              fill-rule="evenodd"
              d="M11.47 7.72a.75.75 0 0 1 1.06 0l7.5 7.5a.75.75 0 1 1-1.06 1.06L12 9.31l-6.97 6.97a.75.75 0 0 1-1.06-1.06l7.5-7.5Z"
              clip-rule="evenodd"
            />
          </svg>
        </div>
      </div>
    </div>
  </div>
</template>
