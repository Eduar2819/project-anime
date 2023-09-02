<template>
        <div class="container my-2">
            <div class="d-flex justify-content-between">
                <span style="font-size: clamp(.5rem, 1.7rem, 1.7rem) !important" class="fw-light">Ultimos episodios</span>
                <div >
                    <span>Hoy</span>
                </div>
            </div>
            <div class="row row-cols-1 row-cols-sm-2 row-cols-lg-4  ">
                <div v-for="item in 20" :key="item" class="col p-0">
                    <div class="card control m-2">
                        <div class="zoom rounded">
                             <img class="rounded" src="../assets/img/jujus.jpg" alt="">
                        </div>
                        <div class="gradiente">
                            <div class="card-img-overlay p-0 gradiente">
                                <div class="info-capi">
                                    <span style="color: white" class="rounded-pill fw-bold capitulo" >
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
        padding: 1px 10px;
        font-size: .7rem;
    }
    .gradiente{
         background: linear-gradient(to bottom, transparent, black)
    }
    .control{
        position: relative;
        padding: 0;
        max-height: 150px;
    }
    .info-capi{
        position: absolute;
        bottom: 0;
        text-align: left;
        margin-left: 5px;
    }
    .zoom{
        overflow: hidden;
    }
    .zoom img{
        min-width: 100%;
        max-height: 150px;
        transition: all .2s ease;
        object-fit: cover;
    }

    .control:hover .zoom img{
        transform: scale(1.2);
        opacity: .5;
    }
</style>
