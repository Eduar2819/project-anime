<template>
        <div class="sidebar">
            <h2 class="sidebar-title">ANIMES EN EMISION
                <i class="mdi mdi-play" style="float: right; font-size: 2rem; line-height: 1.5rem; color: orange;"></i></h2>
            <hr class="sidebar-divider">   
            <ul class="sidebar-list">
                <li><a href="#anime1"><i class="mdi mdi-play-circle"></i>  One piece</a></li>
                <li><a href="#anime2"><i class="mdi mdi-play-circle"></i>  Shadow ikuni</a></li>
                <li><a href="#anime3"><i class="mdi mdi-play-circle"></i>  Hunter X Hunter</a></li>
                <li><a href="#anime3"><i class="mdi mdi-play-circle"></i>  Hunter X Hunter</a></li>
                <li><a href="#anime3"><i class="mdi mdi-play-circle"></i>  Hunter X Hunter</a></li>
                <li><a href="#anime3"><i class="mdi mdi-play-circle"></i>  Hunter X Hunter</a></li>
                <li><a href="#anime3"><i class="mdi mdi-play-circle"></i>  Hunter X Hunter</a></li>
                <li><a href="#anime3"><i class="mdi mdi-play-circle"></i>  Hunter X Hunter</a></li>
                <li><a href="#anime3"><i class="mdi mdi-play-circle"></i>  Hunter X Hunter</a></li>
                <li><a href="#anime3"><i class="mdi mdi-play-circle"></i>  Hunter X Hunter</a></li>
            </ul>
        </div>
  </template>
  
  <script>
  export default {
    
  };
</script>

<style>
.sidebar {
    width: 280px; /* Ajusta el ancho según tus preferencias */
    background-color: #f8f9fa; /* Color de fondo del sidebar */
    padding: 20px;
}

.sidebar-title {
  font-size: 1.2rem; /* Tamaño de fuente del título */
  margin-bottom: 20px; /* Espaciado inferior para separar el título del contenido */
  text-align: left;
}


.sidebar-list {
    list-style: none;
    padding: 0;
    text-align: left;

}

.sidebar-list li {
  margin-bottom: 10px; /* Ajusta el margen inferior entre elementos de la lista */
}

.sidebar-list li a {
  text-decoration: none; /* Quita el subrayado del enlace */
  color: #333; /* Cambia el color del texto del enlace */
  display: block; /* Hace que todo el espacio del elemento sea clicable */
  padding: 1px; /* Añade un poco de espacio alrededor del enlace para hacerlo más clicable */
  transition: color 0.3s;
}
.sidebar-list li a:hover {
 /* background-color: #f0f0f0; /* Cambia el color de fondo cuando se pasa el mouse sobre el enlace */
  color: blue;
}

  </style>
  