<template>
  <input type="submit" :value="value" />
</template>

<script>
export default {
  props: {
    value: String,
  },
};
</script>

<style scoped>
input {
  padding: 10px 100px;
  margin: 10px;
  background: black;
  color: white;
  border-radius: 5px;
  cursor: pointer;
}
</style>
