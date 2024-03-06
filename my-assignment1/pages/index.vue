<template>
  <div class="bg-gray-100 min-h-screen flex flex-col items-center pt-10">
    <div class="w-100 max-w-lg mb-8">
      <input
        type="search"
        placeholder="Search"
        class="w-full p-1 text-base border-2 border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-gray-300"
      />
    </div>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-10 px-6 w-full max-w-4xl">
      <div v-for="index in 4" :key="index" class="bg-white shadow rounded-2xl overflow-hidden">
        <div class="relative pt-4 pb-2 px-4">
          <div class="absolute inset-0 flex items-center justify-center">
            <span class="text-gray-500 text-sm">(Picture)</span>
          </div>
          <div class="w-full bg-gray-200 h-24 rounded-md"></div>
        </div>
        <div class="px-4 pb-6">
          <div class="flex items-center">
            <div class="bg-gray-300 rounded-full h-12 w-12"></div>
            <div class="flex-1 ml-4 space-y-2">
              <div class="h-1 bg-gray-300 rounded w-4/5 mb-2"></div>
              <div class="h-1 bg-gray-300 rounded w-3/4 mb-2"></div>
              <div class="h-1 bg-gray-300 rounded w-2/3"></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">

</script>

<style scoped>

</style>