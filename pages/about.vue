<template>
<section class="text-gray-700 body-font">
  <div class="px-10 py-8 ">
    <nuxt-link to="/" class="inline-flex text-white bg-teal-600 border-0 py-2 px-4 focus:outline-none hover:bg-gray-600 rounded text-base">Go Home</nuxt-link>
  </div>
  <div class="container mx-auto flex px-5 items-center justify-center pt-8 flex-col">

    <img class="lg:w-1/4 md:w-1/3 w-5/6 mb-10 object-cover object-center rounded-full" alt="hero" src="../assets/img/profile.jpg">
    <div class="text-center lg:w-2/3 w-full">

        <h1 class="title-font sm:text-4xl text-3xl py-2 font-medium text-gray-900">Reuben Ninan</h1>
      <!-- <p class="mb-8 leading-relaxed">My name is Reuben Ninan and I am a 19-year-old developer from Toronto. I currently study Software Engineering and Computer Security (B.Eng) at the Lassonde School of Engineering.</p> -->
      <p class="mb-8 leading-relaxed">Below is a timeline of my professional and personal journey for the last few years.</p> 



    </div>

    
  </div>
  <div class="flex justify-center items-center mb-12">
    <Timeline class="md:w-11/12 w-full" />
  </div>



</section>
</template>

<script>
import Timeline from '../components/Timeline'

export default {
  components : {
    Timeline,
  }
  
}
</script>