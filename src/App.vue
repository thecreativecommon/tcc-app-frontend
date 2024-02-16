<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <div class="flex">
    <div class="h-screen p-5 pt-8 w-72 bg-slate-800 text-white">
      <div>
        <!-- Header image goes here-->
        <span class="text-white font-semibold text-2xl">The Creative Common</span>
      </div>
      <div class="pt-4">
        <ul>
          <li class="text-gray-300 text-sm flex items-center gap-x-2 cursor-pointer p-2 hover:bg-slate-700 rounded-md mt-2">
            <span>
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-5 h-5">
                <path d="M10 8a3 3 0 1 0 0-6 3 3 0 0 0 0 6ZM3.465 14.493a1.23 1.23 0 0 0 .41 1.412A9.957 9.957 0 0 0 10 18c2.31 0 4.438-.784 6.131-2.1.43-.333.604-.903.408-1.41a7.002 7.002 0 0 0-13.074.003Z" />
              </svg>
            </span>
            <span>Membership</span>
          </li>
        </ul>
      </div>
    </div>
    <div class="p-7 flex-1">
        <RouterView />
    </div>
  </div>
</template>
