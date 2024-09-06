<template>
  <div class="p-3">
    <h2 class="text-sm">Home / <span class="font-semibold">Project</span></h2>
    <h1 class="font-bold mt-5 text-base">Kanban</h1>

    <!-- Navigation Section -->
    <div class="bg-white p-3 rounded-xl flex justify-between items-center mt-5">
      <div class="flex gap-5 text-sm">
        <h1 class="border border-[#800080] rounded-lg py-1 px-8">Jobs</h1>
        <h1 class="border border-[#800080] rounded-lg py-1 px-8">Contracts</h1>
        <h1 class="bg-[#F2E6F2] font-bold text-[#800080] rounded-lg py-1 px-7">
          Projects
        </h1>
      </div>

      <!-- Search bar for searching within jobs -->
      <div
        class="flex gap-3 p-1 items-center border w-72 border-gray-300 rounded-lg"
      >
        <img
          src="../assets/Test/search.svg"
          alt="Search Icon"
          class="h-4 w-4"
        />
        <input
          type="text"
          class="text-sm text-gray-500 no-underline focus:outline-none w-full"
          placeholder="Search in jobs"
        />
      </div>
    </div>

    <!-- Grid section for different project status -->
    <div class="grid grid-cols-4 gap-20">
      <!-- Column 1 -->
      <div class="mt-6 bg-[#F2F0F7] p-2 rounded-xl w-64 pr-4">
        <h1 class="font-semibold mb-3">In Planning</h1>
        <div class="w-full h-[2px] bg-[#DEDCE2] mb-3" />
        <Grid
          :status="'Draft'"
          :title="'CMS web application for Event Management Company'"
          :bg="'text-[#8A8A8A] font-semibold'"
        />
      </div>

      <!-- Column 2 -->

      <div class="mt-6 bg-[#F2F0F7] p-2 rounded-xl w-64 pr-4">
        <h1 class="font-semibold mb-3">In Execution</h1>
        <div class="w-full h-[2px] bg-[#DEDCE2] mb-3" />

        <div class="flex flex-col gap-4">
          <Grid
            :title="'Android App Development'"
            :status="'Active'"
            :border="'border-t-4 border-t-[#219653]'"
            :bg="'bg-[#E1EEE7] text-[#57AF7D] font-semibold'"
          />
          <Grid
            :title="'Android App Development'"
            :status="'Overdue'"
            :border="'border-t-4 border-t-[#D4A20D]'"
            :bg="'bg-[#FFF9E6] text-[#DAAD2A] font-semibold'"
          />
        </div>
      </div>

      <!-- Column 3 -->
      <div class="mt-6 bg-[#F2F0F7] p-2 rounded-xl w-64 pr-4">
        <h1 class="font-semibold mb-3">Completed</h1>
        <div class="w-full h-[2px] bg-[#DEDCE2] mb-3" />
        <Grid
          :title="'Web App Development'"
          :status="'Active'"
          :border="'border-t-4 border-t-[#219653]'"
          :bg="'bg-[#E1EEE7] text-[#57AF7D] font-semibold'"
        />
      </div>
    </div>
  </div>
</template>

<script setup>
import Grid from "./Grid.vue";
</script>
