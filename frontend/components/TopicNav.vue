<template>
  <!-- Topic Nav -->
  <nav class="w-full py-4 border-t border-b bg-gray-100" x-data="{ open: false }">
    <div class="block sm:hidden">
      <a
        href="#"
        class="block md:hidden text-base font-bold uppercase text-center flex justify-center items-center"
      >
        Topics <i class="fas ml-2" />
      </a>
    </div>
    <div class="w-full flex-grow sm:flex sm:items-center sm:w-auto">
      <div class="w-full container mx-auto flex flex-col sm:flex-row items-center justify-center text-sm font-bold uppercase mt-0 px-6 py-2">
        <a href="#" class="hover:bg-gray-400 rounded py-2 px-4 mx-2">Technology</a>
        <a href="#" class="hover:bg-gray-400 rounded py-2 px-4 mx-2">Automotive</a>
        <a href="#" class="hover:bg-gray-400 rounded py-2 px-4 mx-2">Finance</a>
        <a href="#" class="hover:bg-gray-400 rounded py-2 px-4 mx-2">Politics</a>
        <a href="#" class="hover:bg-gray-400 rounded py-2 px-4 mx-2">Culture</a>
        <a href="#" class="hover:bg-gray-400 rounded py-2 px-4 mx-2">Sports</a>
      </div>
    </div>
  </nav>
</template>
