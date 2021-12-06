<template>
  <Header
    :title="'Hanns Care Anlyze'"
    :detail="'2022 analyze from Jan to Dec'"
  />
  <!-- content -->
  <content>
    <ul>
      <Chart />
      <Chart />
    </ul>
  </content>

  <div class="text-center">
    <Button :value="'提交'" />
    <Button :value="'返回'" />
  </div>
</template>

<script>
import Header from "../organisms/header.vue";
import Button from "../organisms/button.vue";
import Chart from "../organisms/chart.vue";

export default {
  components: {
    Header,
    Button,
    Chart,
  },
};
</script>
