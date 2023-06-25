<template>
    <h1>Two way data binding</h1>
    <input type="text" v-model="count" placeholder="Type here...">
    <h2>{{ count }}</h2>
</template>

<script>
export default {
name:'Twowaybinding',
data() {
    return {
        count: null,
    }
}

}
</script>

<style>

</style>