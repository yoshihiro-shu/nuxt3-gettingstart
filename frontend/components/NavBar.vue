<script setup>

</script>

<template>
  <!-- Top Bar Nav -->
  <nav class="w-full py-4 bg-blue-800 shadow">
    <div class="w-full container mx-auto flex flex-wrap items-center justify-between">
      <nav>
        <ul class="flex items-center justify-between font-bold text-sm text-white uppercase no-underline">
          <li>
            <NuxtLink class="hover:text-gray-200 hover:underline px-4" href="/">
              Home
            </NuxtLink>
          </li>
          <li>
            <NuxtLink class="hover:text-gray-200 hover:underline px-4" href="/about">
              About
            </NuxtLink>
          </li>
          <li>
            <NuxtLink class="hover:text-gray-200 hover:underline px-4" href="/pokemon">
              Pokemon
            </NuxtLink>
          </li>
        </ul>
      </nav>

      <div class="flex items-center text-lg no-underline text-white pr-6">
        <a class="" href="#">
          <i class="fab fa-facebook" />
        </a>
        <a class="pl-6" href="#">
          <i class="fab fa-instagram" />
        </a>
        <a class="pl-6" href="#">
          <i class="fab fa-twitter" />
        </a>
        <a class="pl-6" href="#">
          <i class="fab fa-linkedin" />
        </a>
      </div>
    </div>
  </nav>
</template>
