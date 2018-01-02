<template>
  <div>
    <svg width="420" height="150">
      <g class="bar" v-for="(d, i) in data" :transform="`translate(0, ${21 * i})`">
        <rect :width="d * 10" height="19"/>
      </g>
    </svg>
  </div>
</template>

<script>
export default {
  name: 'bar-chart',
  data () {
    return {
      data: [4, 8, 15, 16, 23]
    }
  }
}
</script>

<style>
.bar {
  fill: #aaa;
  height: 21px;
  transition: fill .3s ease;
  cursor: pointer;
  width: 100%;
}

.bar:hover,
.bar:focus {
  fill: #0074d9;
}
</style>
