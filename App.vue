<template>
  <div id="app">
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
              <router-link class="nav-link" to="/" > Home </router-link>
              <router-link class = "nav-link" to ="/blog"> Blog </router-link>
              <router-link class = "nav-link" to ="/gallery"> Gallery </router-link>
              <router-link class = "nav-link" to ="/contact"> Contact </router-link>
    </nav>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.nav-link {
  color: white;
}
</style>
