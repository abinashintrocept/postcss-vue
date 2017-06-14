<template>
  <div id="app">
    <div class="container">
      <div class="row">
        <div class="column">
          This is column
        </div>
        <div class="column">
          This is column
        </div>
        <div class="column">
          This is column
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss">
:root {
  --container-width: 1170;
  --container-bg: #f2f2f2;
  --grid-columns: 12;
}

  .container {
    background-color: var(--container-bg);
    margin: 0 auto;
    width: calc(var(--container-width) * 1px);
  }

  .row {
    display: flex;
    flex-wrap: wrap;
    width: 100%;
  }
  
  .column {
    flex: 1 1 auto;
  }
</style>
