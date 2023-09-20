<template>
        <div class="sidebar">
          <div class="border-bottom">
            <h2 class="sidebar-title">ANIMES EN EMISION
                <i class="mdi mdi-play" style="float: right; font-size: 2rem; line-height: 1.5rem; color: orange;"></i>
            </h2>
            <button class="rounded-pill" style="background-color: #01bcf3;" type="button" data-bs-toggle="collapse" data-bs-target="#Micollapse" aria-controls="Micollapse" aria-expanded="false">
                <span><i class="mdi mdi-menu border-0" style="color: white;"></i></span>
            </button>
          </div>
          <div id="Micollapse" class="collapse">
            <ul class="sidebar-list p-0" >
                <li><a href="#anime1"><i class="mdi mdi-play-circle"></i> One piece <span class="type tv">anime</span></a></li>
                <li><a href="#anime2"><i class="mdi mdi-play-circle"></i> Shadow ikuni <span class="type tv">anime</span></a></li>
                <li><a href="#anime3"><i class="mdi mdi-play-circle"></i> Hunter X Hunter <span class="type tv">anime</span></a></li>
                <li><a href="#anime3"><i class="mdi mdi-play-circle"></i> Hunter X Hunter <span class="type tv">anime</span></a></li>
                <li><a href="#anime3"><i class="mdi mdi-play-circle"></i> Hunter X Hunter <span class="type tv">anime</span></a></li>
                <li><a href="#anime3"><i class="mdi mdi-play-circle"></i> Hunter X Hunter <span class="type tv">anime</span></a></li>
                <li><a href="#anime3"><i class="mdi mdi-play-circle"></i> Hunter X Hunter <span class="type tv">anime</span></a></li>
                <li><a href="#anime3"><i class="mdi mdi-play-circle"></i> Hunter X Hunter <span class="type tv">anime</span></a></li>
                <li><a href="#anime3"><i class="mdi mdi-play-circle"></i> Hunter X Hunter <span class="type tv">anime</span></a></li>
                <li><a href="#anime3"><i class="mdi mdi-play-circle"></i>  Hunter X Hunter <span class="type tv">anime</span></a></li>
            </ul>
          </div>
        </div>
  </template>
  
  <script>
  export default {
    
  };
</script>

<style scoped>
.sidebar{
    width: 280px; 
    background-color: #f8f9fa; 
    border-radius: 5px;
}

.sidebar-title{
  font-size: 1rem; 
  padding: 15px;
  text-align: left;
  color: #3b4248;
}


.sidebar-list{
    list-style: none;
    padding-top: 15px ;
    text-align: left;

}

.sidebar-list li{
  padding-left: 0;
}
.sidebar-list li a i{
  opacity: .2;
}
.sidebar-list li a{
  display: block;
  position: relative;
  text-decoration: none; 
  color: #3b4248; 
  display: block; 
  padding: 10px 85px 10px 15px;
  transition: color 0.3s;
}

.sidebar-list li a:hover{
  background-color: #f0f0f000;
  color: #01bcf3;
}

.sidebar-list li a:hover i, 
.sidebar-list li a:hover .type
{
  opacity: 1;
}
.type{
  font-size: 10px;
  font-weight: 700;
  line-height: 16px;
  width: 60px;
  text-align: center;
  text-transform: uppercase;
  color: #fff;
  display: inline-block;
  height: 16px;
  border-radius: 8px;
}
.type.tv{
  background-color: #01bcf3;
  border-color: #01bcf3;
}

li .type{
  opacity: .5;
  transition: all .2s;
  position: absolute;
  top: 0;
  bottom: 0;
  margin: auto;
  right: 16px;
}
</style>
  