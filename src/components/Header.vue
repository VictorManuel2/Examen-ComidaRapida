<template>
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
      <a class="navbar-brand" href="#">{{ nombreNegocio }}</a>
      <a class="navbar-brand"> {{ nombreAlumno }} - {{ grupo }} </a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarText"
        aria-controls="navbarText"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarText">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#">Ensaladas</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Arroces</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Pescados</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Carne</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Postres</a>
          </li>
        </ul>
        
      </div>
    </nav>
  </template>
  <script>
  export default {
    props: {
      nombreNegocio: {
        String,
      },
      nombreAlumno: {
        String,
      },
      grupo: {
        String,
      },
    },
  };
  </script>
  

