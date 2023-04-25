<template>
  <div class="home">
    <h1>{{title}}</h1>
    <p> Hello, this is the home page! <br>
    There is nothing else in here just a simple introduction!</p>
  </div>
</template>

<script>
export default {
  name: 'home',
  data () {
    return {
      title: 'Home'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  font-size: 20px;
  font-weight: bold;
  color: red;
}
p {
  border: 2px solid black;
}
</style>
