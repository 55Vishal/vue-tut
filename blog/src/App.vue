<template>
  <img src="./assets/logo.png" alt="Vue logo">
  <HelloWorld msg="Hi There!!!"/>
  <HomePage/>
  <EventPage />

</template>

<script>
import EventPage from './components/EventPage.vue';
import HelloWorld from './components/HelloWorld.vue';
import HomePage from './components/HomePage.vue';
export default {
  name: "App",
  components: {
    HelloWorld,
    HomePage,
    EventPage,
  },
};
</script>

<style scoped>
h1 {
  color: orange;
}
</style>
