<template>
<div class="app">
  <header class="header">
    <h1 class="title">
      TradingView Charting Library and Vue.js Integration Example
    </h1>
  </header>
  <TVChartContainer />
</div>
</template>

<script>
import TVChartContainer from './components/TVChartContainer.vue'
export default {
  name: 'app',
  components: {
    TVChartContainer
  }
}
</script>

<style scoped>
  .app {
    text-align: center;
  }
  .app .header {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 10px 0;
    background-color: #222;
    color: #fff;
  }
  .app .title {
    display: block;
    font-size: 1.5em;
  }
</style>


