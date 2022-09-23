<template>

<Navbar/>

  <card url="https://www.recetasnestle.com.mx/sites/default/files/srh_recipes/50c3741b980c37339842124aa3f38895.jpg" nombre="Mojarra Frita" precio= "$ 100" descripcion="Lo mas Tradicional que puedes degustar"/>
  <card url="https://t2.rg.ltmcdn.com/es/posts/1/3/7/camarones_enchipotlados_35731_600.jpg" nombre="Camarones Enchipoclados" precio= "$ 150" descripcion="Son lo mas delioso de los platillos para Aliviar todo mal"/>
  <card url="https://acapulco.pro/wp-content/uploads/2022/02/pulpo-enamorado-estilo-acapulco2.jpg" nombre="Pulpos" precio= "$ 120" descripcion="Este Platillo es delicioso pulpo cocinado en su punto"/>
  <card url="https://d320djwtwnl5uo.cloudfront.net/recetas/cover/c-cte_ryxIHo0kRf2P1iFjQLvV7Ezs3Ol5pY.png" nombre="Coctel de Camaron" precio= "$ 80" descripcion="Delicioso Coctel de Camaron Listo para comenzar"/>
  <card url="https://i.ytimg.com/vi/vfeypL5Rif8/maxresdefault.jpg" nombre="Filete Empanizado" precio= "$ 90" descripcion="Para un paladar tan sencible como el amor de mama"/>
  <card url="https://gourmetdemexico.com.mx/wp-content/uploads/2022/06/ostiones7.jpg" nombre="Ostines" precio= "$ 50 Orden" descripcion="Estan en su concha, sal y limon al gusto"/>
<br>

<br>
<br>
  <Footer/>

</template>


<style>

</style>

<script>


  import Card from "./components/Card.vue";
  import Navbar from "./components/Navbar.vue";
  import Footer from "./components/Footer.vue"


  export default{
    components: { Card, Navbar, Footer}
  }
</script>

