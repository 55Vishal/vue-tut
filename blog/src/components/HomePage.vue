<template>
<h1>Email: {{ email }} </h1>
<h1> Name: {{ getName() }} </h1>
</template>
    
<script>
export default {
   data() {
    return {
        email: 'email@example.com',
        getName: function() {
            return 'Jhon wick'
        }
    }
   }
}
</script>