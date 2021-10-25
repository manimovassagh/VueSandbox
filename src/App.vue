<template>
  <div>check cleaning</div>
  <h1 v-show="apiData==4"  class="check">test</h1>
  <!-- <div :id=[read.name]>{{read.name}}</div> -->
</template>

<script>

export default {
  name: 'App',

  data(){
    return {
  apiData:4
    }
  }
}


</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.check{
  border: #2c3e50 2px solid;
}
</style>
