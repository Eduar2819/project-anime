<template>
    <footer>
        <div class="content-container">
            <span class="white-text">
                Anime Online
                <span>-Ningún video se encuentra alojado en nuestros servidores</span>
            </span>
            <nav class="oval-nav">
                <ul class="nav-list">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Terminos y Condiciones</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Politica de Provacidad</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Sobre AnimeFLV</a>
                    </li>
                </ul>
            </nav>
            <br>
            <br>


        </div>
    </footer>

</template>

<script>
    export default {

    }

</script>

<style>
.content-container {
    display: flex; /* Utiliza el modelo de caja flexible */
    flex-direction: column; /* Alinea los elementos en columna */
    align-items: flex-start; /* Alinea los elementos a la izquierda */
}

.white-text {
    font-size: 15px;
    margin: 30px;
    display: flex; /* Hace que los elementos estén en línea */
    align-items: center; /* Alinea verticalmente los elementos */
    color: white; /* Color de texto blanco */
}

.white-text span {
    font-size: 15px;
    font-weight: bold;
    color: darkgray;
}


.oval-nav {
    display: inline-block;
    background-color: rgba(0, 0, 0, 0.3);
    border-radius: 50px; /* Ajusta el radio para crear una forma ovalada */
    padding: 10px 20px; /* Ajusta el relleno para la forma ovalada */
    margin: 20px; /* Agrega un margen para separación */
    width: fit-content; /* Ajusta el ancho al contenido */
}

.nav-list {
    list-style: none;
    display: flex;
    align-items: center;
    padding: 0;
    margin: 0; /* Elimina el margen por defecto de la lista */
}

.nav-item {
    margin-right: 15px;
}

.nav-link {
    color: white !important;
    position: relative;
    transition: color 0.3s, border-bottom-color 0.3s;
}


.nav-link:hover {
    border-bottom: 2px solid white;
}



</style>