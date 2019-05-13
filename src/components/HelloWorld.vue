<template>
  <h2>{{msg.toUpperCase()}}</h2>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h2 {
    color: #03A9F4;
  }
</style>
