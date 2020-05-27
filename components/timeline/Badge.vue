<template>
  <div
    class="px-3 h-6 rounded-full text-xs font-semibold flex items-center"
    :class="`bg-${color}-100 text-${color}-500`"
  >
    <span class="w-2 h-2 rounded-full mr-1" :class="`bg-${color}-500`"></span>
    <span>
      {{text}}
    </span>
  </div>
</template>
<script>
export default {
  props: {
    color: {
      type: String,
      default: "teal"
    },
    text : {
      type: String,
      default: ""
    }
  }
};
</script>
