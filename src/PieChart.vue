<template>
  <div>
    <svg width="100" height="100" class="pie-chart">
      <circle r="25" cx="50" cy="50" style="stroke-dasharray: 94.8, 158"/>
    </svg>
  </div>
</template>

<script>
export default {
  name: 'pie-chart',
  data () {
    return {
      data: 10
    }
  }
}
</script>

<style>
.pie-chart {
  transform: rotate(-90deg);
  -webkit-transform: rotate(-90deg);
  background: #ddd;
  border-radius: 100%;
  display: block;
}

.pie-chart circle {
  fill: #ddd;
  stroke: #0074d9;
  stroke-width: 50;
}
</style>
