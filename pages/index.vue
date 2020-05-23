<template>
  <div>
    <Splash/>
    
    <ProjectBoard/>

    <Footer/>

  </div>
</template>

<script>

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
</script>
