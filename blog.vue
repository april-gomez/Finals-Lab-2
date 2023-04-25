<template>
    <div class="blog">
      <h1>{{title}}</h1>
      <p>
        It is a long established fact that a reader will be distracted by the readable content <br>
        of a page when looking at its layout. The point of using Lorem Ipsum is that it has a <br>
        more-or-less normal distribution of letters, as opposed to using 'Content here, content <br>
        here', making it look like readable English. Many desktop publishing packages and web <br>
        page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' <br>
        will uncover many web sites still in their infancy. Various versions have evolved over the years, <br>
        sometimes by accident, sometimes on purpose (injected humour and the like).
      </p>
    </div>
  </template>
  
  <script>
  export default {
    name: 'blog',
    data () {
      return {
        title: 'Blog'
      }
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  p {
    text-align: center;
    border: 2px solid black;
    border-radius: 10px;
  }
  </style>
  