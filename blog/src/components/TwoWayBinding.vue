<template>
  <h1>Two way data binding</h1>
  <input type="text" v-model="count" placeholder="Type here..." />
  <h2>{{ count }}</h2>
</template>

<script>
export default {
  name: "TwoWaybinding",
  data() {
    return {
      count: null,
    };
  },
};
</script>

<style scoped>
h1 {
  color: red;
}
</style>
