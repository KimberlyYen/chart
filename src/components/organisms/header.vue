<template>
  <div class="text-center">
    <h1 class="bg-gray-200 py-4 text-3xl font-bold">{{ title }}</h1>
    <p class="my-5">{{ detail }}</p>
  </div>
</template>

<script>
export default {
  props: {
    title: String,
    detail: String,
  },
};
</script>
