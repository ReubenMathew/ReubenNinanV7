<template>
  <div
    class="px-3 h-6 rounded-full text-xs font-semibold flex items-center"
    :class="`bg-${color}-100 text-${color}-700`"
  >
    <span class="w-2 h-2 rounded-full mr-1 " :class="circle"></span>
    <span>
      <slot></slot>
    </span>
  </div>
</template>
<script>
export default {
  props: {
    color: {
      type: String,
      default: "blue"
    }
  },
  computed: {
    circle() {
      return 'bg-'+this.color+'-400';
    }
  }
};
</script>
