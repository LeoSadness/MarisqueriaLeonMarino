<template>
<body>

<h1>Marisqueria Leon Marino</h1>
<h2>Leonardo Contreras Martinez 10 A</h2>

<div class="navbar">
  <a class="active" href="#"><i class="fa fa-fw fa-home"></i> Cocina</a> 
  <a href="#"><i class="fa fa-fw fa-search"></i> Fotos</a> 
  <a href="#"><i class="fa fa-fw fa-envelope"></i> Contacto</a> 
  <a href="#"><i class="fa fa-fw fa-user"></i>Ver Mis Pedidos</a>
</div>
</body>

</template>


<style>
body {font-family: Arial, Helvetica, sans-serif;}

.navbar {
  width: 100%;
  background-color: #555;
  overflow: auto;
}

.navbar a {
  float: left;
  padding: 12px;
  color: white;
  text-decoration: none;
  font-size: 17px;
}

.navbar a:hover {
  background-color: #000;
}

.active {
  background-color: #1F3AFB;
}

@media screen and (max-width: 500px) {
  .navbar a {
    float: none;
    display: block;
  }
}
</style>

<script>    
</script>