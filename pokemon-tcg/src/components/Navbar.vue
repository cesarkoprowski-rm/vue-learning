<template>
  <nav class="bg-black border-b border-gray-500">
      <div class="mx-auto max-w-7xl px-2 sm:px-6 lg:px-8">
        <div class="flex h-20 items-center justify-between">
          <div class="flex flex-1 items-center justify-center md:items-stretch md:justify-start">
            <a class="flex flex-shrink-0 items-center mr-4" href="index.html">
              <img class="h-10 w-auto" v-bind:src="logo" alt="Vue Jobs" />
              <span class="hidden md:block text-white text-2xl font-bold ml-2">Pokémon TCG</span>
            </a>
            <div class="flex-grow flex justify-center items-center">
              <span>
                <input
                  type="text"
                  placeholder="Buscar..."
                  class="
                    w-64
                    px-4 py-1
                    rounded-md
                    border border-gray-300
                    focus:outline-none
                    focus:ring-2
                    focus:ring-blue-500
                    hidden md:block
                    placeholder:text-base
                  "
                />
              </span>
            </div>
            <div class="md:ml-auto">
              <div class="flex space-x-2">
              <a
                href="index.html"
                class="text-white hover:bg-gray-800 hover:text-white rounded-md px-3 py-2"
                >Home</a
              >
              <a
                href="jobs.html"
                class="text-white hover:bg-gray-800 hover:text-white rounded-md px-3 py-2"
                >Jobs</a
              >
              <a
                href="add-job.html"
                class="text-white hover:bg-gray-800 hover:text-white rounded-md px-3 py-2"
                >Add Job</a
              >
            </div>
          </div>
        </div>
      </div>
    </div>
  </nav>
</template>
 
<script setup>
  import logo from '@/assets/img/logo.png'
</script>