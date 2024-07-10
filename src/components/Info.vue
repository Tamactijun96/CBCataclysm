<template>
  <div class="infoContainer justify-content-center d-flex pt-4 mt-3">
    <div class="row containerRank1">
      <div class="col containerRank2">
        <h3>Vuelve Alamuerte</h3>
        <div class="heading"><h1>Tu aventura clásica continúa</h1></div>
        <div class="size-description">
          <p class="description">
            Has derrotado a los ejércitos no-muertos del Rey Exánime y has
            acabado con el reinado de Arthas. Ahora, Alamuerte el Rompemundos
            surge del corazón de la Vorágine y desata su ira. Todo arderá bajo
            la sombra de sus alas.
          </p>
        </div>
      </div>
      <videoComponent></videoComponent>
    </div>
  </div>
</template>

<script>
import videoComponent from "./VideoComponents.vue";

export default {
  components: { videoComponent },
  name: "infocontainer",
};
</script>

<style scoped>
.infoContainer{
  margin-bottom: -89px;
}
.heading {
  width: 600px;
  text-align: left;
  
}

.size-description {
  width: 600px;
  text-align: left;
}

.containerRank1 {
  width: 1700px;
  
  margin-bottom: 90px;
}

.containerRank2 {
  padding-left: 60px;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-self: center;
  
  
}


p.description {
  padding-top: 24px;
  color: #ffffffb3;
  filter: drop-shadow(4px 2px 4px rgba(0, 0, 0, 0.4));
  letter-spacing: 1px;
  font-size: 19px;
}
</style>
