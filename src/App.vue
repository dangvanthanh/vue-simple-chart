<template>
  <div class="app">
    <bar-chart></bar-chart>
    <line-chart></line-chart>
  </div>
</template>

<script>
import BarChart from './components/BarChart.vue'
import LineChart from './components/LineChart.vue'

export default {
  name: 'app',
  components: {
    BarChart,
    LineChart
  }
}
</script>

<style>
</style>
