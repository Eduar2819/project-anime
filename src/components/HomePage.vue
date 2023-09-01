<template>
        <div class="container my-2">
            <div class="d-flex justify-content-between">
                <span style="font-size:1.7rem" class="fw-light">Ultimos episodios</span>
                <div >
                    <span>Hoy</span>
                </div>
            </div>
            <div class="row row-cols-1 row row-cols-sm-2 row row-cols-lg-4  ">
                <div v-for="item in 20" :key="item" class="col">
                    <div class="card control">
                        <img class="card-img" src="../assets/img/jujus.jpg" alt="">
                        <div class="gradiente">
                            <div class="card-img-overlay p-0 gradiente">
                                <div class="info-capi">
                                    <span class="rounded-pill fw-bold capitulo text-start" >
                                    Episodio 7
                                    </span>
                                    <h5 class="fw-bold" style="font-size: 1.3rem; color: white">Jujutsu kaisen</h5>
                                </div>
                            </div>  
                        </div>  
                    </div>
                </div>
            </div>
        </div>
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
    .capitulo{
        background-color: #ff7e00; 
        line-height: 2rem; 
        padding: 0 8px;
        font-size: .7rem;
    }
    .gradiente{
         background: linear-gradient(to bottom, transparent, black)
    }
    .control{
        position: relative;
        padding: 0;
        margin: 5px 0;
        max-width: 100%;
    }
    .info-capi{
        position: absolute;
        bottom: 0;
        text-align: left;
        margin-left: 5px;
    }
</style>
