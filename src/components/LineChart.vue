<template>
  <div>
    <svg viewBox="0 0 500 100" class="line-chart">
      <polyline
        fill="none"
        stroke="#0074d9"
        stroke-width="2"
        points="
          0, 120
          20, 60
          40, 80
          60, 20
          80, 100
          100, 40"/>
    </svg>
  </div>
</template>

<script>
export default {
  data () {
    return {
      data: [120, 60, 80, 20, 100, 40]
    }
  }
}
</script>

<style>
.line-chart {
  background: #fff;
  width: 500px;
  height: 100px;
  border-left: 1px dotted #333;
  border-bottom: 1px dotted #333;
  padding: 20px 20px 0;
}
</style>
