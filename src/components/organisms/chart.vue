<template>
  <canvas ref="root" width="400" height="400"></canvas>
</template>

<script>
import { onMounted } from "vue";
import { getCurrentInstance } from "vue";
import Chart from "chart.js/auto";

export default {
  setup() {
    //   Make sure we are do initialize after component mounted, aka on the screen.
    onMounted(() => {
      // 1.  get current component instance
      function getCurrentInstance(data) {
        console.log(data);
      }
      // 2. the DOM element will be assigned to the refs in instance
      //   const canvas =
      // 3. initialize Chart JS by passing, DOM element and data
    });
  },
};
</script>
