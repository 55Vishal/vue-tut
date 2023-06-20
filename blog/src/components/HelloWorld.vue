<template>
  <div class="hello">
    <h1>Hello World</h1>
    <h2>Pass by props: {{ msg }} </h2>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
 props : {
msg: String
 }
}
</script>

