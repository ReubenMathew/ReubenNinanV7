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
import TaskCard from "./timeline/TaskCard.vue";
export default {
  name: "App",
  components: {
    TaskCard,
  },
  data() {
    return {
      columns: [
        {
          title: "2020",
          tasks: [
            {
              id: 1,
              title: "Joined RBC as a Data Science Intern",
              date: "May",
            },
            {
              id: 2,
              title: "Created SodaDB",
              date: "Apr",
            },
            {
              id: 3,
              title: "Worked on VennFX",
              date: "Jan-Apr",
            },
          ]
        },
        {
          title: "2019",
          tasks: [
            {
              id: 4,
              title: "Joined RBC as a Data Science Intern",
              date: "Apr",
            },
          ]
        },
        {
          title: "2018",
          tasks: [
            {
              id: 5,
              title: "Joined Lassonde School of Engineering to Study Software Engineering",
              date: "Sept",
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
