<template>
  <div class="app">
    <h1>Simple Chart SVG using Vue.js</h1>
    <h2>Bar Chart</h2>
    <bar-chart></bar-chart>
    <h2>Line Chart</h2>
    <line-chart></line-chart>
    <h2>Pie Chart</h2>
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
.app {
  max-width: 768px;
  margin: 0 auto;
}
</style>
