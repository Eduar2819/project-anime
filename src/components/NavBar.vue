<template>
    <nav class="navbar navbar-expand-lg" style="background-color: #3b4248">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">
                <img src="../assets/img/logo.png" alt="">
            </a>
            <button class="navbar-toggler rounded-pill" style="background-color: #01bcf3;" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span><i class="mdi mdi-menu border-0" style="color: white;"></i></span>
            </button>
            <div class="collapse navbar-collapse justify-content-end" id="navbarSupportedContent">
                <div class="d-flex">
                    <a class="link mx-1" href="#">INICIO</a>
                    <a class="link mx-2" href="#">DIRECTORIO ANIME</a>
                </div>
                <form class="d-flex" role="search">
                    <div class="input-group mx-2" style="width: 200px">
                        <input type="text" class="form-control rounded-start-pill" style="outline: none;" placeholder="Buscar..." aria-label="Buscar..." aria-describedby="basic-addon2">
                        <span class="input-group-text rounded-end-circle" id="basic-addon2"><i class="mdi mdi-magnify" style="font-size:20px"></i></span>
                    </div>
                    <button class="btn" style="background-color: rgba(0,0,0,.2);" type="submit"><i class="mdi mdi-account" style="color:white; font-size:20px"></i><span class="mx-1" style="color: white">LOGIN</span></button>
                </form>
            </div>
        </div>
        </nav>
</template>
<script>

</script>
<style scoped>
    .link{
        text-decoration: none;
        font-weight: bold;
        color: white;
    }
    .input-group-text{
        position: relative;
        background-color: white;
         border-left: none; 
         
    }
</style>
