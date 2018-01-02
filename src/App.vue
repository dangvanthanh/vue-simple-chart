<template>
  <div class="app">
    <bar-chart></bar-chart>
    <line-chart></line-chart>
    <pie-chart></pie-chart>
  </div>
</template>

<script>
import BarChart from './components/BarChart.vue'
import LineChart from './components/LineChart.vue'
import PieChart from './components/PieChart.vue'

export default {
  name: 'app',
  components: {
    BarChart,
    LineChart,
    PieChart
  }
}
</script>

<style>
</style>
