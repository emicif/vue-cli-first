<template>
  <div class="jumbotron">
      <p class="text-jumbotron">{{msg}}</p>
  </div>
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
<style scoped lang="scss">
.jumbotron {
  margin: 40px auto;
  background-color: aquamarine;
  height: 500px;
}

.text-jumbotron {
  color: red;
  font-size: 30px;
  line-height: 500px;
  vertical-align: middle;
}
</style>
