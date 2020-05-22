<template>
<div class="px-6">
  <div class="flex max-w-md shadow-lg bg-gray-900 rounded-lg overflow-hidden">
     <div class="w-full p-6 text-white">
        <p class="font-bold mt-4 rounded-full text-base uppercase">Toronto, Ontario</p>
        <p class="text-4xl md:text-5xl name font-semibold text-yellow-500">Reuben Ninan</p>
        <p class="text-2xl mt-2 mb-6 leading-none font-light">Software Engineer</p>

        <div class=" text-gray-800 text-lg font-bold flex flex-wrap">
            <div class="py-2 ">
                <a href="https://github.com/ReubenMathew/" class="bg-yellow-500 transition duration-200 ease-in-out hover:text-yellow-500 border border-yellow-500 hover:bg-transparent px-4 py-1 shadow-lg rounded-full">Github</a>
            </div>
            <div class="py-2 sm:px-4 xs:px-0">
                <a href="https://twitter.com/NinanReuben" class="bg-yellow-500 transition duration-200 ease-in-out hover:text-yellow-500 border border-yellow-500 hover:bg-transparent px-4 py-1 shadow-lg rounded-full">Twitter</a>
            </div>
            <div class="py-2">
                <nuxt-link to="resume" class="bg-yellow-500 transition duration-200 ease-in-out hover:text-yellow-500 border border-yellow-500 hover:bg-transparent px-4 py-1 shadow-lg rounded-full">Resume</nuxt-link>
            </div>
        </div>

    </div>
  </div>
</div>
</template>