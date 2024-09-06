<template>
  <div class="bg-[#F6F9FB] flex">
    <!-- Sidebar Header -->
    <div class="w-60 p-3">
      <Header />
    </div>

    <!-- Main Section -->
    <div class="flex-1">
      <div class="p-3">
        <Searchbar />
        <Content/>
      </div>
    </div>
  </div>
</template>

<script setup>
import Header from './components/Header.vue';
import Searchbar from './components/Searchbar.vue';
import Content from './components/Content.vue';
</script>

<style scoped>
/* Any additional global styles */
</style>
