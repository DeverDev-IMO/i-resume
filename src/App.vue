<script setup>
import HelloWorld from "./components/HelloWorld.vue";
import Navbar from "./components/Navbar.vue";
import Drawer from "./components/Drawer.vue";
import Sidebar from "./components/Sidebar.vue";
</script>

<template>
  <div class="grid gap-1 grid-cols-1 ">
    <div>
      <Sidebar />
    </div>
    <div class="flex items-center justify-center rounded bg-gray-50 h-28 dark:bg-gray-800">
      <p class="text-2xl text-gray-400 dark:text-gray-500">text</p>
    </div>
  </div>


</template>

<!-- <style scoped></style> -->
