<template>
  <div
    class="bg-white rounded-lg text-sm flex flex-col gap-8 p-4 font-semibold text-[#ACACAC] relative"
  >
    <!-- Logo Section -->
    <div>
      <img
        src="../assets/Test/28353ee3c525adf38323a2b01195730a.png"
        alt="Main Logo"
        class="w-36 mx-auto"
      />
    </div>

    <!-- Icon To Close Open Navbar -->
    <div
      class="absolute -right-4 top-12 border rounded-full border-gray-100 shadow-xl "
    >
      <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 24 24"
        fill="currentColor"
        class="h-8 w-8 bg-white rounded-full p-2"
      >
        <path
          fill-rule="evenodd"
          d="M7.72 12.53a.75.75 0 0 1 0-1.06l7.5-7.5a.75.75 0 1 1 1.06 1.06L9.31 12l6.97 6.97a.75.75 0 1 1-1.06 1.06l-7.5-7.5Z"
          clip-rule="evenodd"
        />
      </svg>
    </div>

    <!-- Navigation Menu -->
    <div class="mt-3">
      <ul class="grid grid-cols-1 gap-1 items-center">
        <li class="flex items-center gap-3 mx-4 p-2 hover:bg-gray-100 rounded">
          <img
            src="../assets/Test/apps 1.png"
            alt="Dashboard"
            class="w-4 h-4"
          />
          <span class="text-left flex-1">Dashboard</span>
        </li>
        <li class="flex items-center gap-3 mx-4 p-2 hover:bg-gray-100 rounded">
          <img src="../assets/Test/home 1.png" alt="Home" class="w-4 h-4" />
          <span class="text-left flex-1">Home</span>
        </li>
        <li
          class="flex items-center gap-3 mx-4 p-2 bg-[#F2E6F2] text-[#800080] rounded"
        >
          <img
            src="../assets/Test/briefcase 1.svg"
            alt="Jobs"
            class="w-4 h-4"
          />
          <span class="text-left flex-1">Jobs</span>
        </li>
        <li class="flex items-center gap-3 mx-4 p-2 hover:bg-gray-100 rounded">
          <img
            src="../assets/Test/comments 1.svg"
            alt="Chats"
            class="w-4 h-4"
          />
          <span class="text-left flex-1">Chats</span>
        </li>
        <li class="flex items-center gap-3 mx-4 p-2 hover:bg-gray-100 rounded">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            class="w-4 h-4 text-black"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M18 18.72a9.094 9.094 0 0 0 3.741-.479 3 3 0 0 0-4.682-2.72m.94 3.198.001.031c0 .225-.012.447-.037.666A11.944 11.944 0 0 1 12 21c-2.17 0-4.207-.576-5.963-1.584A6.062 6.062 0 0 1 6 18.719m12 0a5.971 5.971 0 0 0-.941-3.197m0 0A5.995 5.995 0 0 0 12 12.75a5.995 5.995 0 0 0-5.058 2.772m0 0a3 3 0 0 0-4.681 2.72 8.986 8.986 0 0 0 3.74.477m.94-3.197a5.971 5.971 0 0 0-.94 3.197M15 6.75a3 3 0 1 1-6 0 3 3 0 0 1 6 0Zm6 3a2.25 2.25 0 1 1-4.5 0 2.25 2.25 0 0 1 4.5 0Zm-13.5 0a2.25 2.25 0 1 1-4.5 0 2.25 2.25 0 0 1 4.5 0Z"
            />
          </svg>

          <span class="text-left flex-1">My Network</span>
        </li>
        <li class="flex items-center gap-3 mx-4 p-2 hover:bg-gray-100 rounded">
          <img
            src="../assets/Test/refer-arrow 1.svg"
            alt="Refer a Friend"
            class="w-4 h-4"
          />
          <span class="text-left flex-1">Refer a Friend</span>
        </li>
        <li class="flex items-center gap-3 mx-4 p-2 hover:bg-gray-100 rounded">
          <img src="../assets/Test/ticket 1.svg" alt="Coupon" class="w-4 h-4" />
          <span class="text-left flex-1">Coupon</span>
        </li>
        <li class="flex items-center gap-3 mx-4 p-2 hover:bg-gray-100 rounded">
          <img
            src="../assets/Test/settings (1) 1.svg"
            alt="Settings"
            class="w-4 h-4"
          />
          <span class="text-left flex-1">Settings</span>
        </li>
      </ul>
    </div>
    
    <!-- Mobile App Section -->
    <div class="flex flex-col p-4 m-4 justify-center bg-[#800080] rounded-lg text-center">
      <h1 class="p-2 text-white">Try Mobile App Version</h1>
      <button class="bg-white rounded-2xl px-4 p-2 text-[#800080]">Download</button>
    </div>
  </div>
</template>
