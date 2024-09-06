<template>
  <div :class="`bg-white rounded-xl p-2 pr-4 ${props.border}`">
    <div class="flex justify-between items-center mb-3">
      <h1 class="font-semibold text-gray-400 text-sm">#CON22148</h1>
      <h1 :class="`bg-[#F2F0F7] px-3 py-1 rounded-xl text-sm ${props.bg}`">
        {{ props.status }}
      </h1>
    </div>

    <div class="mb-3">
      <h1 class="text-sm font-semibold">
        {{ props.title }}
      </h1>
      <p class="text-sm text-gray-400">Web, Mobile & Software Development</p>
    </div>

    <div class="mt-3">
      <div class="flex justify-between mb-2">
        <div>
          <p class="text-gray-400 text-xs">Industry Vertical</p>
          <h2 class="text-sm font-semibold">Ecommerce</h2>
        </div>
        <div>
          <p class="text-gray-400 text-xs">Type</p>
          <h2 class="text-sm font-semibold">Small Job</h2>
        </div>
      </div>

      <p class="text-gray-400 text-sm">Requirements Count</p>
      <h2 class="text-sm">1</h2>

      <div class="flex justify-between mt-1">
        <div>
          <p class="text-gray-400 text-xs">Published Date</p>
          <h2 class="text-xs font-semibold">2024-05-28</h2>
        </div>
        <div>
          <p class="text-gray-400 text-xs">Start Date</p>
          <h2 class="text-xs font-semibold mb-1">2024-05-28</h2>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
const props = defineProps({
  title: String,
  status: String,
  border: String,
  bg: String,
});
</script>
