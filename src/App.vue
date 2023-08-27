<template>
<body style="background-color: #eeeeee">
  <nav>
    <Navbar/>
  </nav>
  <div>
    <div class="container image rounded">
      <div class="titulo">
        <h1 class="fw-light"><span class="fw-bold">AnimeFLV</span> tu fuente de anime online gratis en HD</h1>
    </div>
    </div>
    <HomePage/>
  </div>
    
</body>
  
</template>

<script>
import HomePage from './components/HomePage.vue'
import Navbar from './components/NavBar.vue'

export default {
  name: 'App',
  components: {
    HomePage,
    Navbar
  }
}
</script>

<style>
*, :before, :after {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}
body{
  height: 100vh;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.image{
  margin-top: 20px ;
  background-image: url('./assets/img/bgb.jpg');
  padding: 10px 20px;
  min-height: 50px;
  border-bottom: 3px solid #01bcf3;
}
.titulo {
  margin: 0px auto;
  color: white;
}
.titulo h1{
  display: block;
  font-size: 25px;
  margin-bottom: 0;
  letter-spacing: -1;
}
</style>
