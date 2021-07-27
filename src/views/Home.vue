<template>
  <div class="container">
    <div class="row completo">
      <div class="col-sm d-flex align-items-center">
        <div>
          <h1><b>Cooking Beats</b> tu <b>Comunidad</b>, tu <b>Musica</b></h1>
          <p class="size: 24px">
            La plataforma Latinoamericana de distribución de contenido, que te permite crear en comunidad.
          </p>
        </div>
      </div>
      <div class="col-sm d-flex align-items-center">
        <img src="imagen1.png" alt="" style="width: 100%;" />
      </div>
    </div>
    <div class="row completo">
      <div class="col-sm d-flex align-items-center">
        <img src="imagen2.png" width="100%" alt="">
      </div>
      <div class="col-sm d-flex align-items-center">
        <div>
          <h1>Un <b>entorno sencillo</b> para <b>Usuarios</b> iniciados.</h1>
          <p>No pierdas el tiempo en aprender a usar nustro sistema y concentrece en vender o en comprar si es lo que necesitas.</p>
        </div>
      </div>
    </div>
    <div class="row completo">
      <div class="col-sm d-flex align-items-center">
        <div>
          <h1>Medios de <b>Pago Locales</b>.</h1>
          <p class="size: 24px">
            Incorporamos medios de pago locales para poder perder el minimo dinero y tiempo posible. Proximamente ampliaremos a mas medios de pago.
          </p>
        </div>
      </div>
      <div class="col-sm d-flex align-items-center">
        <img src="imagen3.png" alt="" style="width: 90%;" />
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
//import Reproductor from "@/components/Reproductor.vue";
export default {
  name: "Home",
};
</script>
<style>
.completo,
.container {
  height: 100%;
  width: 100%;
  top: 10%;
  right: 5%;
}
</style>
