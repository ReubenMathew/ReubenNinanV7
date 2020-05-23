<template>
<div>
    <div class="bg-gray-200 text-center font-normal text-6xl pt-10 pb-4 ">
      My Work
    </div>
    <div class="bg-gray-200 min-h-full px-2 flex flex-wrap pb-8 justify-center">
      <div v-for="(project, index) in projects" v-bind:key="(project, index)">
          <ProjectCard :doc="project"/>
      </div>
    </div>
</div>
</template>

<script>
import ProjectCard from './ProjectCard'

export default {
    components: {
        ProjectCard,
    },
    data: () => ({
    projects: [
      {
          imageURL: 'https://images.unsplash.com/photo-1505740420928-5e560c06d30e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80',
          title: 'Amateur Hour - Developer Podcast',  
          content: 'A technology focused podcast covering topics such as software development, career advice, and other tips for amateurs like me.',
          tags : [
            {name: 'Website', link:'https://anchor.fm/amateur-hour'},
            {name: 'Spotify', link:'https://open.spotify.com/show/6G01A4kQpffGEIH6aw26mb'}
          ]
      },
      {
          imageURL: 'https://images.unsplash.com/photo-1517959105821-eaf2591984ca?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1952&q=80',
          title: 'SodaDB',
          content: 'A Beginner-Friendly Concurrent Datastore built with Go',
          tags: [
            {name: 'Source Code', link: 'https://github.com/ReubenMathew/SodaDB'},
            {name: 'Download', link: 'https://github.com/ReubenMathew/SodaDB/releases/tag/v1.0'},
          ],
      },
      {
          imageURL: 'https://images.unsplash.com/photo-1558494949-ef010cbdcc31?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2691&q=80',
          title: 'Pingo',
          content: 'A minimalist commandline-interface for ICMP Echo Requests, commonly known as PING.',
          tags: [
            {name: 'Source Code', link: 'https://github.com/ReubenMathew/pingo'},
            {name: 'Download', link: 'https://github.com/ReubenMathew/pingo/releases/tag/v1'},
          ],
      },
      {
          imageURL: 'https://images.unsplash.com/photo-1462899006636-339e08d1844e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1950&q=80',
          title: 'FinTech Template',
          content: 'A business landing page with a modern fintech feel, built with Vue and TailwindCSS',
          tags: [
            {name: 'Source Code', link: 'https://github.com/ReubenMathew/business_template'},
            {name: 'Live Link', link: 'https://business-template.now.sh/'},
          ],
      },
      {
          imageURL: 'https://images.unsplash.com/photo-1486312338219-ce68d2c6f44d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1952&q=80',
          title: 'VennFX',
          content: 'A cross-platform Venn Diagram desktop application, Built with JavaFX.',
          tags: [
            {name: 'Source Code', link: 'https://github.com/ReubenMathew/VennFX'},
            {name: 'Download', link: 'https://github.com/EECS2311-Team8/SoftwareDevelopmentProject/releases/tag/vF'},
          ],
      },
      {
          imageURL: 'https://images.unsplash.com/photo-1532153975070-2e9ab71f1b14?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1950&q=80',
          title: 'DocScanner',
          content: 'A simple document scanner utilizing an OpenCV edge detection engine.',
          tags: [
            {name: 'Source Code', link: 'https://github.com/ReubenMathew/DocScanner'},
          ],
      },
    ]
  })
}
</script>