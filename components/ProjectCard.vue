<template>
<div class = "p-4 lg:transition lg:duration-300 lg:ease-in-out transform hover:scale-105">
<div class="max-w-xl rounded-lg border border-gray-300 overflow-hidden shadow-md">
  <img class="w-full h-auto" :src="doc.imageURL" alt="Project Splash Image">
  <div class="px-6 pt-6">
    <div class="font-bold text-xl mb-2">{{doc.title}}</div>
    <p class="text-grey-darker text-base">
      {{doc.content}}  
    </p>
  </div>
  <div class="px-5 pb-6 pt-2 flex flex-wrap text-gray-900">
    <a :href="tag.link" v-for="tag in doc.tags" v-bind:key="tag" class="transition duration-300 ease-in-out hover:bg-gray-100 bg-yellow-500 shadow-md rounded-full mt-2 px-3 py-2 text-sm font-semibold mr-2">{{tag.name}}</a>
  </div>
</div>
</div>
</template>

<script>
export default {
    props: ['doc'],
}
</script>