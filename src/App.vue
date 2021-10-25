<template>
  <div>check cleaning</div>
  <h1 v-show="apiData==4"  class="check">test</h1>
  <h2 v-for="(name,index) in apiData" v-bind:key="index">{{name}}</h2>
  <!-- <div :id=[read.name]>{{read.name}}</div> -->
  
</template>

<script>

export default {
  name: 'App',

  data(){
    return {
  apiData:['mani','sahar']
    }
  }
}
// function getData(data) {
//   fetch('https://jsonplaceholder.typicode.com/todos/1')
//   .then(response => response.json())
//   .then(json => data=json)
  
// }

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
