<template>
  <!--Pie de pagina-->
  <footer class="container-fluid text-center foot">
    <div class="copyrights">
      <p class="white-txt">
        Store Control Copyright © 2021 <br /><br />
        <img class="footimg" src="../assets/logo.png" alt="Logo" />
      </p>
      <hr class="dark-line" />
      <a class="link" href="#"
        ><i class="fa fa-facebook-square fa-3x" id="iconf"></i
      ></a>
      <a class="link" href="#"
        ><i class="fa fa-twitter-square fa-3x" id="iconf"></i
      ></a>
      <a class="link" href="#"
        ><i class="fa fa-instagram fa-3x" id="iconf"></i
      ></a>
      <a class="link" href="#"
        ><i class="fa fa-whatsapp fa-3x" id="iconf"></i
      ></a>
      <br /><br />
    </div>
    <p class="white-txt" id="parrafof">
      ¡Store Control cumple con tus necesidades contactanos en nuestras redes
      sociales para mas informacion! ▲
    </p>
  </footer>
</template>

<script>
export default {};
</script>

<style>
/* Css del footer o pie de pagina */
.copyrights {
  margin-top: 660px;
}

footer.container-fluid.text-center.foot {
  background: #383838;
  height: 315px;
}

.dark-line {
  border-top: 1px solid #525252;
}

.white-txt {
  color: #fff;
}

a.link {
  padding: 0px 15px;
}

.footimg {
  width: 5rem;
}
</style>