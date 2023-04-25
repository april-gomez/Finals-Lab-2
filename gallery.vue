<template>
    <div id="gallery">
      <h1>{{title}}</h1>
      <h3> Here are some cats! </h3>
      <div class = "gallery__img">
        <div class = "gridscroll">
          <h3> Siamese Cat </h3>
          <img v-bind:src="Siamese">
          <h3> Persian Cat </h3>
          <img v-bind:src="Persian">
          <h3> Sphynx Cat </h3>
          <img v-bind:src="Sphynx">
          <h3> Ragdoll Cat </h3>
          <img v-bind:src="Ragdoll">
        </div>
      </div>
    </div>
  </template>
  
  <script>
  import Siamese_img from "D:/2176-AJZG/finals/finalprj/src/assets/Siamese.jpg"
  import Persian_img from "D:/2176-AJZG/finals/finalprj/src/assets/Persian.jpg"
  import Sphynx_img from "D:/2176-AJZG/finals/finalprj/src/assets/Sphynx.jpg"
  import Ragdoll_img from "D:/2176-AJZG/finals/finalprj/src/assets/Ragdoll.jpg"

  export default {
    name: 'gallery',
    data () {
      return {
        title: 'Gallery',
        Siamese: Siamese_img,
        Persian: Persian_img,
        Sphynx: Sphynx_img,
        Ragdoll: Ragdoll_img,
      }
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  #gallery{
    width: 900px;
    display: inline-block;
}
img{
    width: 100%;
    display: inline-flex;
    border-style: solid;
    border-color: black;
}
    h3 {
  color: red;
}
  </style>
  