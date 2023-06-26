<template>
  <h1>Get Input Field Values</h1>
  <input v-model="email" type="text" placeholder="Enter Email" />
  <br />
  <br />
  <input v-model="password" type="password" placeholder="Enter Password" />
  <br /><br />
  <button v-on:click="getData()" type="button">Get Value</button>
</template>

<script>
export default {
  data() {
    return {
      email: null,
      password: null,
    };
  },
  methods: {
    getData() {
      console.log("Values: " ,this.email , this.password);
    },
  },
};
</script>

<style scoped>
h1 {
  color: blueviolet;
}
</style>
