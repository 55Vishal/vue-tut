<template>
  <h1>Get Input Field Values</h1>
  <input v-model="email" type="text" placeholder="Enter Email" />
  <br />
  <br />
  <input v-model="password" type="password" placeholder="Enter Password" />
  <br /><br />
  <button v-on:click="getData()" type="button">Get Value</button>
  <br />
  <br />
  <h1>Get checkbox and radio buttons value</h1>
  <h3>Technology</h3>
  <label for="java">Java</label>
  <input type="checkbox" value="java" v-model="technology" id="java" />
  <label for="JavaScript">JavaScript</label>
  <input
    type="checkbox"
    value="JavaScript"
    v-model="technology"
    id="JavaScript"
  />
  <label for="PHP">PHP</label>
  <input type="checkbox" value="PHP" v-model="technology" id="PHP" />
<br> <br>

<h3>What is your profession</h3>
<label for="student">Student</label>
<input type="radio" name="profession" v-model="profession" value="Student" id="student">

<label for="developer">Developer</label>
<input type="radio" name="profession" v-model="profession" value="Developer" id="developer">
<br><br>
  
  <h4>Selected Technology: {{ technology }}</h4>
  <h4>Selected Profession: {{ profession }}</h4>
</template>

<script>
export default {
  data() {
    return {
      email: null,
      password: null,
      technology: [],
      profession: null,
    };
  },
  methods: {
    getData() {
      console.log("Values: ", this.email, this.password);
    },
  },
};
</script>

<style scoped>
h1 {
  color: blueviolet;
}
</style>
