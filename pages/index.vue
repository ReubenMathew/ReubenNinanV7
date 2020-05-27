<template>
  <div>
    

    <Splash id="main"/>
    
    <ProjectBoard/>

    <Footer/>

  </div>
</template>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>

<script >

import Footer from '../components/Footer'
import Splash from '../components/Splash'
import ProjectCard from '../components/ProjectCard'
import ProjectBoard from '../components/ProjectBoard'

export default {
  components: {
    Splash,
    Footer,
    ProjectCard,
    ProjectBoard,
  },
  
}

// window.onload = function() {
//   document.getElementById('main').style.display = 'none';
// };

</script>
