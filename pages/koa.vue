<template>
  <div id="app">
    <div class="flex justify-center">
    
      <div class="min-h-full flex overflow-x-scroll py-6">
        <div
          v-for="column in columns"
          :key="column.title"
          class="bg-gray-100 rounded-lg px-3 py-3 column-width rounded mr-4"
        >
          <p class="text-gray-700 font-semibold font-sans tracking-wide text-base">{{column.title}}</p>
          <!-- Draggable component comes from vuedraggable. It provides drag & drop functionality -->
        <task-card
              v-for="(task) in column.tasks"
              :key="task.id"
              :task="task"
              class="mt-3 cursor-text"
            ></task-card>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import TaskCard from "../components/timeline/TaskCard.vue";
export default {
  name: "App",
  components: {
    TaskCard,
  },
  data() {
    return {
      columns: [
        {
          title: "About Me",
          tasks: [
            {
              id: 1,
              title: "In love with da cutest lil bean 💖",
              date: "Current",
            },
            {
              title: "👨🏽‍🍳 19-year-old living in Toronto, Ontario",
            },
            {
              title: "🎓 Studying Software Engineering and Computer Security (B.Eng) 👨🏽‍🔬 at York University"
            },
            {
              title: "Design 🎨, cyber-security 🔐 and product management 📦",
              date: "My Interests"
            },
            {
              title: "⚙ Python, Java, Go, JavaScript",
              date: "Languages I use"
            },
            {
              title:'🛠 Kubernetes, Docker, Kompose, Redis, Celery, RabbitMQ',
              date: "Distributed Systems Technologies"
            },
            {
              title: "🖥 TailwindCSS, NuxtJS, Vercel Now",
              date: "This website was built with"
            }

          ]
        },
        {
          title: "2020",
          tasks: [

            {
              id: 1,
              title: "🏦 Data Science Intern at RBC",
              date: "May-Aug",
            },
            {
              id: 2,
              title: "Created SodaDB, a beginner friendly datastore 📦",
              date: "May",
            },
            {
              id: 2,
              title: "Made my own Podcast for Developers (Amateur Hour) 🎧",
              date: "Apr",
            },
            {
              id: 2,
              title: "Created pingo, a simple ping client 📦",
              date: "Apr",
            },
            {
              id: 3,
              title: "Worked on VennFX, an intuitive idea-formation app 📦",
              date: "Jan-Apr",
            },
          ]
        },
        {
          title: "2019 🐨",
          tasks: [
            {
              id: 4,
              title: "Found the love of my life ❤",
              date: "Jan",
            },
            {
              id: 4,
              title: "🏦 Data Science Intern at RBC",
              date: "Apr-Aug",
            },
          ]
        },
        {
          title: "2018",
          tasks: [
            {
              id: 5,
              title: "🎓 Joined Lassonde School of Engineering to Study Software Engineering",
              date: "Sept",
            },
            {
              id: 5,
              title: "👨🏽‍🏫 Taught robotics, coding and STEM concepts to kids K-12",
              date: "Jun-Aug",
            },
            {
              id: 6,
              title: "Organized WolfHacks Hackathon in Brampton, Ontario 🐺",
              date: "March",
            },
          ]
        },
        {
          title: "Past",
          tasks: [
            {
              id: 6,
              title: "Competed in Vex & First Robotics Competition 🤖",
              date: "2015-2018",
            },
            {
              id: 6,
              title: "Started Coding 👨🏽‍💻",
              date: "2011",
            },
          ]
        },
      ]
    };
  }
};
</script>

<style scoped>
.column-width {
  min-width: 320px;
  width: 320px;
}
/* Unfortunately @apply cannot be setup in codesandbox, 
but you'd use "@apply border opacity-50 border-blue-500 bg-gray-200" here */
.ghost-card {
  opacity: 0.5;
  background: #F7FAFC;
  border: 1px solid #4299e1;
}
</style>
