<template>
<gmap-map
  :center="{lat:35.664334, lng:139.750129}"
  :zoom="18"
  map-type-id="terrain"
  style="width: 500px; height: 300px"
></gmap-map>
</template>

<script>
  export default {
    name: 'App'
  }
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>
