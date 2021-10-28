<template >
  <div>
    <h1>This is a Footer of My App</h1>
    <input type="text" v-model="inputData" />
    <h1>{{ inputData }}</h1>
    <h1 @click="changeName">{{ name }}</h1>
  </div>
</template>
<script>
export default {
  data() {
    return {
      name: "mani",
      alternateName: "some",
      inputData: "",
    };
  },
  methods: {
    changeName() {
      if (this.name == "mani") {
        this.name = this.alternateName;
      } else {
        this.name = "mani";
      }
    },
  },
};
</script>
<style >
</style>