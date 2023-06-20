<template>
  <img src="./assets/logo.png" alt="Vue logo">
  <HelloWorld msg="Hi There!!!"/>
  <HomePage/>

</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import HomePage from './components/HomePage.vue';
export default {
  name: "App",
  components: {
    HelloWorld,
    HomePage,
  },
};
</script>

<style scoped>
h1 {
  color: orange;
}
</style>
