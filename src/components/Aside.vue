<template>
<!--Menu barra lateral-->
  <aside class="aside">
    <div class="list-group" id="lateral">
      <label class="list-group-item bg-info"><span>Acerca de nosotros</span></label>
      <a href="#" class="list-group-item"><i class="fa fa-calendar"></i> <span>Eventos</span></a>
      <a href="#" class="list-group-item"><i class="fa fa-check"></i> <span>Casos de exito</span></a>
      <a href="#" class="list-group-item"><i class="fa fa-question-circle"></i> <span>Ayuda</span></a>
      <a href="#" class="list-group-item"><i class="fa fa-users"></i> <span>Clientes</span></a>
    </div>
  </aside>
</template>

<script>
export default {

}
</script>

<style>
.list-group {
     
    margin:auto;
    float:left;
    padding-top:20px;
   }
   .lead {
    
    margin:auto;
    left:0;
    right:0;
    padding-top:10%;
   }
   label{
    font-size: 20px;
   }
   #lateral{
       
       margin-top: 60px;
   }
</style>