<template>
  <img src="./assets/logo.png" alt="Vue logo">
  <HelloWorld msg="Hi There!!!"/>
  <HomePage/>
  <EventPage />
  <TwoWayBindings />
</template>

<script>
import EventPage from './components/EventPage.vue';
import HelloWorld from './components/HelloWorld.vue';
import HomePage from './components/HomePage.vue';
import TwoWayBindings from './components/TwoWayBinding.vue';
export default {
  name: "App",
  components: {
    HelloWorld,
    HomePage,
    EventPage,
    TwoWayBindings,
  },
};
</script>

<style scoped>
h1 {
  color: orange;
}
</style>
