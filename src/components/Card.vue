<template>
    <div class="cuadro">
      <div class="card" style="width: 18rem">
        <imagen>
          <img class="card-img-top img-fluid" v-bind:src="url" :alt="nombre" />
        </imagen>
        <div class="card-body">
          <h5 class="card-title">{{ nombre }}</h5>
          <p class="card-text">
            {{ descripcion }}
          </p>
        </div>
      </div>
    </div>
  </template>
  <script>
  import Imagen from "./Imagen.vue";
  export default {
    props: {
      url: {
        String,
      },
      nombre: {
        String,
      },
      descripcion: {
        String,
      },
      costo: {
        String,
      },
    },
    components: { Imagen },
  };
  </script>
  <style scoped>
  .cuadro{
    display: inline-block;
    text-align: center;
    border: 1px solid #f2f2f2;
    padding: 1%;
    border-radius: 5px;
    margin: 4px;
  }
  </style>
  