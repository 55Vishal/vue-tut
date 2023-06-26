<template>
  <h1>Email (from data): {{ email }}</h1>
  <h1>Name (from methods): {{ getName("Jhon") }}</h1>
  <h1>All Data: {{ getData().email }}</h1>
</template>

<script>
export default {
  data() {
    return {
      email: "email@example1.com",
    };
  },
  methods: {
    getName(name) {
      return name;
    },
    getData() {
      return {
        name: "xyz",
        email: "email@example2.com",
      };
    },
  },
};
</script>
