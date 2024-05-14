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
        Navigation
        <ul class="px-2">
          <li class="text-gray-300 text-sm flex items-center gap-x-2 cursor-pointer p-2 hover:bg-slate-700 rounded-md mt-2">
            <span>
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-5 h-5">
                <path d="M10 8a3 3 0 1 0 0-6 3 3 0 0 0 0 6ZM3.465 14.493a1.23 1.23 0 0 0 .41 1.412A9.957 9.957 0 0 0 10 18c2.31 0 4.438-.784 6.131-2.1.43-.333.604-.903.408-1.41a7.002 7.002 0 0 0-13.074.003Z" />
              </svg>
            </span>
            <span>Membership</span>
          </li>
          <li class="text-gray-300 text-sm flex items-center gap-x-2 cursor-pointer p-2 hover:bg-slate-700 rounded-md">
            <span>
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round" d="M9 17.25v1.007a3 3 0 0 1-.879 2.122L7.5 21h9l-.621-.621A3 3 0 0 1 15 18.257V17.25m6-12V15a2.25 2.25 0 0 1-2.25 2.25H5.25A2.25 2.25 0 0 1 3 15V5.25m18 0A2.25 2.25 0 0 0 18.75 3H5.25A2.25 2.25 0 0 0 3 5.25m18 0V12a2.25 2.25 0 0 1-2.25 2.25H5.25A2.25 2.25 0 0 1 3 12V5.25" />
              </svg>
            </span>
            <span>Inventory</span>
          </li>
        
          

        </ul>
      </div>
    </div>
    <div class="p-7 flex-1">
        <RouterView />
    </div>
  </div>
</template>
