<template>
  <div>check cleaning</div>
  {{ name.last }}
  <!-- <div :id=[read.name]>{{read.name}}</div> -->
  <Greet></Greet>
  <h1>{{name.first}}</h1>
</template>

<script>

import Greet from "./components/Greet.vue";


export default {
  name: "App",
  components: { Greet },

  data() {
    return {
      name: {first:'mani',last:'movassagh'},
    };
  },
};


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
.check {
  border: #2c3e50 2px solid;
}
</style>
