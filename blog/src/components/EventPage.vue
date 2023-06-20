<template>

    <h1>Event Page</h1>
    <button @click="getData('Button 1 clicked')">Click here</button>
    <button @dblclick="getData('Button double clicked')">Click here</button>
    <button @click="addCount()">Increment</button>
    <h2>{{ count }}</h2>
    </template>

      <!-- -----------**********----------   -->

    <script>
     export default {
        name: "EventPage",
        data(){
            return{
              count: 0
            }
        },
        methods: {
            getData(data) {
                alert(data)
            },
            addCount(){
                this.count = this.count+1
            }
        }
     }
    </script>

      <!-- -----------**********----------   -->

<style scoped>

h1 {
    color:orange
}

</style>