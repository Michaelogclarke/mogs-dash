<template>
    <div class="dashboard bg-gray-900 text-white min-h-screen">
      <div class="p-4">
        <h1 class="text-2xl font-semibold mb-4">Personal Dashboard</h1>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
          <div class="module bg-gray-800 p-4 rounded-lg">
            <h2 class="text-lg font-semibold mb-2">Habit Tracking</h2>
            </div>
          <div class="module bg-gray-800 p-4 rounded-lg">
            <h2 class="text-lg font-semibold mb-2">Notes</h2>
            </div>
          <div class="module bg-gray-800 p-4 rounded-lg">
            <h2 class="text-lg font-semibold mb-2">Workout Tracking</h2>
            </div>
          </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Dashboard',
  };
  </script>