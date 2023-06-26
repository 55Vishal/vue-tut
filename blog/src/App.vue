<template>
  <img src="./assets/logo.png" alt="Vue logo" />
  <HelloWorld msg="Hi There!!!" />
  <HomePage />
  <EventPage />
  <TwoWayBindings />
  <InputValue />
  
</template>

<script>
import EventPage from "./components/EventPage.vue";
import HelloWorld from "./components/HelloWorld.vue";
import HomePage from "./components/HomePage.vue";
import TwoWayBindings from "./components/TwoWayBinding.vue";
import InputValue from "./components/InputValue.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    HomePage,
    EventPage,
    TwoWayBindings,
    InputValue,
  },
};
</script>

<style scoped>
h1 {
  color: orange;
}
</style>
